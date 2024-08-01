### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ProductNoticesStore.ClearOldNotices | avg | 2ms | 57ms | 55ms | 3253.18
| PostStore.AnalyticsPostCount | avg | 256ms | 2.253s | 1.997s | 780.66
| DraftStore.Delete | avg | 3ms | 21ms | 18ms | 703.63
| EmojiStore.Search | avg | 18ms | 110ms | 92ms | 513.55
| ChannelStore.GetMembers | avg | 21ms | 128ms | 107ms | 502.40
| ChannelStore.CreateSidebarCategory | avg | 58ms | 202ms | 144ms | 247.95
| TeamStore.GetMany | avg | 89ms | 260ms | 171ms | 191.18
| ThreadStore.MarkAllAsReadByTeam | avg | 4ms | 11ms | 7ms | 176.70
| LicenseStore.GetAll | avg | 85ms | 234ms | 149ms | 174.29
| ChannelStore.AnalyticsTypeCount | avg | 100ms | 238ms | 138ms | 137.50
| TeamStore.AnalyticsTeamCount | avg | 149ms | 333ms | 184ms | 123.60
| PluginStore.Get | avg | 102ms | 219ms | 117ms | 115.03
| RoleStore.ChannelHigherScopedPermissions | avg | 90ms | 134ms | 44ms | 48.97
| UserStore.AnalyticsActiveCount | avg | 596ms | 853ms | 257ms | 43.13
| UserStore.GetProfilesInChannel | avg | 115ms | 164ms | 49ms | 42.74
| PostStore.GetPostsByIds | avg | 135ms | 190ms | 55ms | 40.75
| ThreadStore.Get | avg | 144ms | 202ms | 58ms | 40.18
| EmojiStore.GetMultipleByName | avg | 83ms | 115ms | 32ms | 38.36
| ChannelStore.Save | avg | 163ms | 212ms | 49ms | 30.06
| ChannelStore.GetMembersForUserWithPagination | avg | 255ms | 316ms | 61ms | 23.93
| BotStore.Get | avg | 120ms | 147ms | 27ms | 22.48
| TeamStore.GetActiveMemberCount | avg | 433ms | 525ms | 92ms | 21.26
| FileInfoStore.SetContent | avg | 15ms | 18ms | 3ms | 19.50
| DraftStore.GetDraftsForUser | avg | 229ms | 270ms | 41ms | 17.87
| JobStore.GetCountByStatusAndType | avg | 119ms | 136ms | 17ms | 14.32
| PreferenceStore.DeleteCategoryAndName | avg | 17ms | 19ms | 2ms | 11.45
| PostStore.Delete | avg | 149ms | 165ms | 16ms | 10.71
| ChannelStore.GetChannelsByIds | avg | 159ms | 170ms | 11ms | 6.92
| UserStore.Get | avg | 50ms | 52ms | 2ms | 4.00
| UserStore.Count | avg | 349ms | 359ms | 10ms | 2.86
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ProductNoticesStore.ClearOldNotices | p99 | 5ms | 247ms | 242ms | 4887.15
| ChannelStore.GetMembers | p99 | 25ms | 970ms | 945ms | 3801.56
| PostStore.AnalyticsPostCount | p99 | 498ms | 4.925s | 4.427s | 889.60
| LicenseStore.GetAll | p99 | 246ms | 2.365s | 2.119s | 863.13
| DraftStore.Delete | p99 | 5ms | 25ms | 20ms | 404.04
| ThreadStore.MarkAllAsReadByTeam | p99 | 10ms | 48ms | 38ms | 385.79
| UserStore.GetMany | p99 | 490ms | 2.095s | 1.605s | 327.27
| TeamStore.GetMany | p99 | 243ms | 975ms | 732ms | 301.54
| UserStore.GetProfilesInChannel | p99 | 480ms | 1.57s | 1.09s | 227.08
| RoleStore.ChannelHigherScopedPermissions | p99 | 498ms | 1.585s | 1.087s | 218.49
| EmojiStore.Search | p99 | 97ms | 247ms | 150ms | 154.62
| DraftStore.Get | p99 | 100ms | 241ms | 141ms | 141.71
| PreferenceStore.DeleteCategoryAndName | p99 | 96ms | 224ms | 128ms | 132.87
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 97ms | 224ms | 127ms | 130.59
| TeamStore.GetActiveMemberCount | p99 | 989ms | 2.155s | 1.166s | 117.93
| PostStore.GetPostsByIds | p99 | 248ms | 495ms | 247ms | 99.57
| ChannelStore.Save | p99 | 961ms | 1.915s | 954ms | 99.24
| ChannelStore.AnalyticsTypeCount | p99 | 475ms | 940ms | 465ms | 97.89
| JobStore.GetNewestJobByStatusesAndType | p99 | 913ms | 1.795s | 882ms | 96.57
| PostPersistentNotificationStore.Get | p99 | 47ms | 78ms | 31ms | 65.96
| ThreadStore.Get | p99 | 1.755s | 2.29s | 535ms | 30.48
| JobStore.UpdateStatusOptimistically | p99 | 65ms | 83ms | 18ms | 27.69
| PostAcknowledgementStore.GetForPost | p99 | 832ms | 1.06s | 228ms | 27.40
| FileInfoStore.SetContent | p99 | 170ms | 199ms | 29ms | 17.05
| FileInfoStore.Save | p99 | 91ms | 96ms | 5ms | 5.47
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 985ms | 1.034s | 49ms | 4.97
| PluginStore.Get | p99 | 470ms | 491ms | 21ms | 4.47
| PostStore.Update | p99 | 232ms | 242ms | 10ms | 4.32
| UserStore.AnalyticsActiveCount | p99 | 2.35s | 2.44s | 90ms | 3.83
| UserStore.Get | p99 | 637ms | 657ms | 20ms | 3.14
| ChannelStore.CreateSidebarCategory | p99 | 244ms | 249ms | 5ms | 2.05
| UserStore.Count | p99 | 971ms | 981ms | 10ms | 1.03
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | avg | 146ms | 0s | -146ms | -100.06
| RetentionPolicyStore.GetAll | avg | 148ms | 0s | -148ms | -99.87
| ChannelStore.GetMemberCountsByGroup | avg | 17ms | 0s | -17ms | -98.89
| BotStore.Save | avg | 3ms | 0s | -3ms | -89.64
| PostStore.GetPostReminders | avg | 20ms | 7ms | -13ms | -65.14
| UserAccessTokenStore.GetByToken | avg | 121ms | 51ms | -70ms | -58.07
| UserStore.GetProfilesNotInChannel | avg | 282ms | 120ms | -162ms | -57.44
| DraftStore.Get | avg | 59ms | 29ms | -30ms | -51.08
| UserStore.AnalyticsGetInactiveUsersCount | avg | 222ms | 115ms | -107ms | -48.10
| JobStore.GetAllByTypePage | avg | 245ms | 128ms | -117ms | -47.72
| PluginStore.List | avg | 201ms | 116ms | -85ms | -42.32
| DraftStore.Upsert | avg | 5ms | 3ms | -2ms | -41.03
| PostStore.GetPostReminderMetadata | avg | 113ms | 67ms | -46ms | -40.83
| LinkMetadataStore.Save | avg | 15ms | 9ms | -6ms | -38.95
| SessionStore.GetSessionsExpired | avg | 149ms | 92ms | -57ms | -38.26
| JobStore.Save | avg | 11ms | 7ms | -4ms | -37.60
| ChannelStore.UpdateSidebarCategories | avg | 394ms | 253ms | -141ms | -35.82
| StatusStore.UpdateExpiredDNDStatuses | avg | 14ms | 10ms | -4ms | -29.34
| ComplianceStore.MessageExport | avg | 133ms | 94ms | -39ms | -29.28
| JobStore.UpdateOptimistically | avg | 14ms | 10ms | -4ms | -29.08
| ChannelStore.GetSidebarCategory | avg | 170ms | 122ms | -48ms | -28.23
| PostPersistentNotificationStore.Get | avg | 7ms | 5ms | -2ms | -27.92
| JobStore.UpdateStatus | avg | 8ms | 6ms | -2ms | -26.51
| PostPersistentNotificationStore.DeleteExpired | avg | 8ms | 6ms | -2ms | -25.59
| JobStore.UpdateStatusOptimistically | avg | 8ms | 6ms | -2ms | -23.54
| SessionStore.Remove | avg | 9ms | 7ms | -2ms | -22.97
| PostPriorityStore.GetForPost | avg | 140ms | 110ms | -30ms | -21.48
| ReactionStore.GetForPost | avg | 151ms | 119ms | -32ms | -21.15
| ChannelStore.GetChannelUnread | avg | 126ms | 100ms | -26ms | -20.69
| ChannelStore.GetTeamChannels | avg | 252ms | 203ms | -49ms | -19.44
| TeamStore.GetTotalMemberCount | avg | 530ms | 432ms | -98ms | -18.50
| PostStore.SetPostReminder | avg | 16ms | 13ms | -3ms | -18.27
| UserStore.GetByUsername | avg | 143ms | 117ms | -26ms | -18.18
| ThreadStore.UpdateMembership | avg | 12ms | 10ms | -2ms | -17.05
| ChannelStore.GetPublicChannelsForTeam | avg | 185ms | 154ms | -31ms | -16.73
| PostStore.SearchPostsForUser | avg | 233ms | 194ms | -39ms | -16.72
| PluginStore.SetWithOptions | avg | 12ms | 10ms | -2ms | -16.49
| PostStore.GetPostsAfter | avg | 116ms | 97ms | -19ms | -16.42
| ChannelStore.GetMember | avg | 13ms | 11ms | -2ms | -15.98
| EmojiStore.GetByName | avg | 148ms | 126ms | -22ms | -14.91
| UserStore.Update | avg | 15ms | 13ms | -2ms | -13.48
| FileInfoStore.GetForPost | avg | 149ms | 130ms | -19ms | -12.79
| PostStore.Get | avg | 243ms | 212ms | -31ms | -12.75
| PostAcknowledgementStore.GetForPosts | avg | 215ms | 188ms | -27ms | -12.58
| PostPriorityStore.GetForPosts | avg | 221ms | 194ms | -27ms | -12.21
| PostStore.GetPostsByThread | avg | 141ms | 124ms | -17ms | -12.02
| ChannelStore.UpdateLastViewedAt | avg | 17ms | 15ms | -2ms | -11.68
| PostPersistentNotificationStore.UpdateLastActivity | avg | 35ms | 31ms | -4ms | -11.31
| ChannelStore.GetMemberCount | avg | 508ms | 452ms | -56ms | -11.02
| ChannelStore.GetMembersForUser | avg | 139ms | 124ms | -15ms | -10.79
| UserStore.IsEmpty | avg | 56ms | 50ms | -6ms | -10.74
| PostStore.Save | avg | 28ms | 25ms | -3ms | -10.72
| ThreadStore.MaintainMembership | avg | 19ms | 17ms | -2ms | -10.70
| ChannelStore.GetPinnedPostCount | avg | 132ms | 118ms | -14ms | -10.60
| ChannelStore.SearchGroupChannels | avg | 163ms | 146ms | -17ms | -10.42
| ChannelStore.GetChannelsByUser | avg | 126ms | 113ms | -13ms | -10.28
| StatusStore.GetByIds | avg | 156ms | 140ms | -16ms | -10.27
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 20ms | 18ms | -2ms | -9.98
| GroupStore.GetByName | avg | 81ms | 73ms | -8ms | -9.92
| PostStore.GetPostsSince | avg | 182ms | 164ms | -18ms | -9.88
| StatusStore.Get | avg | 71ms | 64ms | -7ms | -9.87
| UserStore.GetAllProfilesInChannel | avg | 1.149s | 1.037s | -112ms | -9.75
| ThreadStore.GetTeamsUnreadForUser | avg | 145ms | 131ms | -14ms | -9.64
| ThreadStore.GetThreadFollowers | avg | 146ms | 132ms | -14ms | -9.61
| ThreadStore.GetThreadUnreadReplyCount | avg | 149ms | 135ms | -14ms | -9.38
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 267ms | 242ms | -25ms | -9.35
| PostStore.GetPosts | avg | 98ms | 89ms | -9ms | -9.17
| ThreadStore.GetThreadForUser | avg | 207ms | 188ms | -19ms | -9.17
| ChannelStore.GetChannels | avg | 142ms | 129ms | -13ms | -9.15
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 253ms | 230ms | -23ms | -9.08
| UserStore.GetMany | avg | 156ms | 142ms | -14ms | -8.98
| PreferenceStore.Save | avg | 22ms | 20ms | -2ms | -8.93
| ThreadStore.GetTotalThreads | avg | 112ms | 102ms | -10ms | -8.93
| PreferenceStore.Get | avg | 134ms | 122ms | -12ms | -8.92
| PostPersistentNotificationStore.GetSingle | avg | 146ms | 133ms | -13ms | -8.92
| FileInfoStore.Get | avg | 101ms | 92ms | -9ms | -8.91
| ThreadStore.GetThreadsForUser | avg | 158ms | 144ms | -14ms | -8.84
| ChannelStore.GetMemberForPost | avg | 159ms | 145ms | -14ms | -8.81
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 125ms | 114ms | -11ms | -8.79
| SessionStore.GetLRUSessions | avg | 104ms | 95ms | -9ms | -8.69
| PostStore.GetPostsBefore | avg | 139ms | 127ms | -12ms | -8.63
| GroupStore.GetGroups | avg | 140ms | 128ms | -12ms | -8.59
| ChannelStore.AutocompleteInTeamForSearch | avg | 584ms | 535ms | -49ms | -8.40
| UserStore.AutocompleteUsersInChannel | avg | 680ms | 623ms | -57ms | -8.38
| TeamStore.GetTeamsForUser | avg | 84ms | 77ms | -7ms | -8.37
| ProductNoticesStore.View | avg | 61ms | 56ms | -5ms | -8.26
| WebhookStore.GetOutgoingByTeam | avg | 148ms | 136ms | -12ms | -8.13
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 739ms | 679ms | -60ms | -8.12
| ThreadStore.GetTotalUnreadMentions | avg | 112ms | 103ms | -9ms | -8.05
| ChannelStore.Autocomplete | avg | 3.557s | 3.277s | -280ms | -7.87
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 115ms | 106ms | -9ms | -7.85
| ChannelStore.GetFileCount | avg | 102ms | 94ms | -8ms | -7.82
| PostStore.GetSingle | avg | 129ms | 119ms | -10ms | -7.78
| UserStore.GetUnreadCount | avg | 118ms | 109ms | -9ms | -7.64
| PreferenceStore.GetAll | avg | 158ms | 146ms | -12ms | -7.61
| ChannelStore.GetGuestCount | avg | 145ms | 134ms | -11ms | -7.57
| UserStore.GetProfileByIds | avg | 81ms | 75ms | -6ms | -7.39
| ThreadStore.GetMembershipForUser | avg | 137ms | 127ms | -10ms | -7.30
| PostStore.GetEtag | avg | 151ms | 140ms | -11ms | -7.28
| TeamStore.Get | avg | 125ms | 116ms | -9ms | -7.23
| UserStore.Search | avg | 360ms | 334ms | -26ms | -7.22
| ThreadStore.GetTotalUnreadThreads | avg | 111ms | 103ms | -8ms | -7.19
| ChannelStore.GetMemberLastViewedAt | avg | 97ms | 90ms | -7ms | -7.18
| TeamStore.GetChannelUnreadsForAllTeams | avg | 112ms | 104ms | -8ms | -7.13
| PostAcknowledgementStore.GetForPost | avg | 116ms | 108ms | -8ms | -6.90
| LinkMetadataStore.Get | avg | 131ms | 122ms | -9ms | -6.85
| UserStore.GetProfilesByUsernames | avg | 111ms | 104ms | -7ms | -6.28
| SessionStore.Get | avg | 114ms | 107ms | -7ms | -6.13
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 115ms | 108ms | -7ms | -6.11
| ChannelStore.Get | avg | 181ms | 170ms | -11ms | -6.07
| ChannelStore.SaveMember | avg | 449ms | 422ms | -27ms | -6.01
| SessionStore.Save | avg | 103ms | 97ms | -6ms | -5.81
| ChannelStore.GetByName | avg | 105ms | 99ms | -6ms | -5.70
| UserStore.GetAllProfiles | avg | 88ms | 83ms | -5ms | -5.69
| UserStore.GetForLogin | avg | 96ms | 91ms | -5ms | -5.21
| ChannelStore.CreateDirectChannel | avg | 446ms | 423ms | -23ms | -5.16
| JobStore.GetAllByStatus | avg | 140ms | 133ms | -7ms | -4.99
| UserTermsOfServiceStore.GetByUser | avg | 127ms | 121ms | -6ms | -4.71
| ProductNoticesStore.GetViews | avg | 458ms | 437ms | -21ms | -4.58
| TeamStore.GetTeamsByUserId | avg | 118ms | 113ms | -5ms | -4.25
| ChannelStore.CreateInitialSidebarCategories | avg | 128ms | 123ms | -5ms | -3.91
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 103ms | 99ms | -4ms | -3.89
| ChannelStore.GetAllChannelMembersForUser | avg | 78ms | 75ms | -3ms | -3.85
| TeamStore.SaveMember | avg | 217ms | 209ms | -8ms | -3.69
| TeamStore.GetAllPage | avg | 112ms | 108ms | -4ms | -3.57
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 148ms | 143ms | -5ms | -3.37
| UserStore.Save | avg | 95ms | 92ms | -3ms | -3.17
| JobStore.GetNewestJobByStatusesAndType | avg | 114ms | 111ms | -3ms | -2.64
| JobStore.Get | avg | 164ms | 160ms | -4ms | -2.44
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 249ms | 0s | -249ms | -100.20
| RetentionPolicyStore.GetAll | p99 | 495ms | 0s | -495ms | -100.00
| ChannelStore.GetMemberCountsByGroup | p99 | 98ms | 0s | -98ms | -100.00
| PostStore.GetPostReminders | p99 | 437ms | 44ms | -393ms | -89.83
| JobStore.GetAllByTypePage | p99 | 6.202s | 899ms | -5.303s | -85.50
| UserStore.GetProfilesNotInChannel | p99 | 2.365s | 486ms | -1.879s | -79.45
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 975ms | 247ms | -728ms | -74.67
| ChannelStore.GetSidebarCategory | p99 | 1.6s | 630ms | -970ms | -60.62
| TeamStore.GetTotalMemberCount | p99 | 2.365s | 981ms | -1.384s | -58.52
| PostStore.SetPostReminder | p99 | 220ms | 93ms | -127ms | -57.73
| PostPersistentNotificationStore.DeleteExpired | p99 | 187ms | 90ms | -97ms | -51.87
| CommandWebhookStore.Cleanup | p99 | 10ms | 5ms | -5ms | -51.02
| DraftStore.Upsert | p99 | 10ms | 5ms | -5ms | -50.73
| ChannelStore.GetPublicChannelsForTeam | p99 | 1.74s | 879ms | -861ms | -49.48
| UserStore.Update | p99 | 190ms | 99ms | -91ms | -48.02
| LinkMetadataStore.Save | p99 | 183ms | 97ms | -86ms | -46.89
| PluginStore.List | p99 | 1.72s | 917ms | -803ms | -46.69
| SessionStore.Remove | p99 | 47ms | 25ms | -22ms | -46.55
| PostStore.GetPostReminderMetadata | p99 | 795ms | 433ms | -362ms | -45.54
| JobStore.UpdateOptimistically | p99 | 174ms | 95ms | -79ms | -45.48
| PostStore.Delete | p99 | 890ms | 486ms | -404ms | -45.39
| UserStore.GetAllProfilesInChannel | p99 | 4.164s | 2.486s | -1.678s | -40.29
| ChannelStore.AutocompleteInTeamForSearch | p99 | 3.998s | 2.438s | -1.56s | -39.02
| FileInfoStore.GetForPost | p99 | 1.59s | 1.013s | -577ms | -36.29
| PostStore.GetPostsAfter | p99 | 1.364s | 878ms | -486ms | -35.64
| ThreadStore.GetThreadUnreadReplyCount | p99 | 1.515s | 995ms | -520ms | -34.32
| PluginStore.SetWithOptions | p99 | 158ms | 104ms | -54ms | -34.10
| ThreadStore.MarkAllAsReadByChannels | p99 | 153ms | 102ms | -51ms | -33.28
| ThreadStore.GetThreadFollowers | p99 | 1.462s | 988ms | -474ms | -32.43
| ChannelStore.SearchGroupChannels | p99 | 1.561s | 1.07s | -491ms | -31.46
| JobStore.GetCountByStatusAndType | p99 | 1.285s | 883ms | -402ms | -31.28
| StatusStore.GetByIds | p99 | 1.87s | 1.302s | -568ms | -30.37
| PostStore.GetPostsSince | p99 | 1.515s | 1.068s | -447ms | -29.51
| EmojiStore.GetByName | p99 | 1.314s | 942ms | -372ms | -28.32
| StatusStore.SaveOrUpdate | p99 | 188ms | 136ms | -52ms | -27.66
| WebhookStore.GetOutgoingByTeam | p99 | 1.382s | 1.003s | -379ms | -27.43
| LinkMetadataStore.Get | p99 | 1.332s | 979ms | -353ms | -26.50
| ReactionStore.GetForPost | p99 | 1.233s | 909ms | -324ms | -26.28
| JobStore.Save | p99 | 89ms | 66ms | -23ms | -25.94
| ChannelStore.CreateDirectChannel | p99 | 3.344s | 2.486s | -858ms | -25.66
| ThreadStore.GetThreadsForUser | p99 | 1.454s | 1.088s | -366ms | -25.17
| ThreadStore.UpdateMembership | p99 | 129ms | 97ms | -32ms | -24.75
| GroupStore.GetGroups | p99 | 1.299s | 984ms | -315ms | -24.24
| PostStore.GetPostsByThread | p99 | 1.302s | 987ms | -315ms | -24.19
| PostPriorityStore.GetForPost | p99 | 1s | 762ms | -238ms | -23.80
| PostStore.GetSingle | p99 | 1.277s | 976ms | -301ms | -23.57
| PostPersistentNotificationStore.GetSingle | p99 | 1.254s | 969ms | -285ms | -22.72
| PluginStore.Delete | p99 | 65ms | 51ms | -14ms | -21.58
| ChannelStore.GetMembersForUser | p99 | 1.227s | 964ms | -263ms | -21.43
| ChannelStore.GetMemberForPost | p99 | 1.574s | 1.246s | -328ms | -20.84
| ThreadStore.GetTeamsUnreadForUser | p99 | 1.757s | 1.402s | -355ms | -20.21
| PostStore.SearchPostsForUser | p99 | 1.837s | 1.466s | -371ms | -20.20
| ThreadStore.GetMembershipForUser | p99 | 1.235s | 989ms | -246ms | -19.92
| ComplianceStore.MessageExport | p99 | 1.65s | 1.325s | -325ms | -19.70
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 3.011s | 2.458s | -553ms | -18.37
| ChannelStore.UpdateSidebarCategories | p99 | 2.268s | 1.87s | -398ms | -17.55
| FileInfoStore.AttachToPost | p99 | 137ms | 114ms | -23ms | -16.79
| ClusterDiscoveryStore.SetLastPingAt | p99 | 83ms | 69ms | -14ms | -16.79
| TeamStore.GetMember | p99 | 173ms | 144ms | -29ms | -16.75
| ChannelStore.GetChannels | p99 | 1.168s | 976ms | -192ms | -16.44
| TeamStore.Get | p99 | 1.14s | 968ms | -172ms | -15.09
| ChannelStore.Get | p99 | 1.689s | 1.441s | -248ms | -14.68
| PreferenceStore.Get | p99 | 1.118s | 964ms | -154ms | -13.78
| PostStore.GetEtag | p99 | 1.178s | 1.019s | -159ms | -13.50
| UserAccessTokenStore.GetByToken | p99 | 485ms | 420ms | -65ms | -13.40
| StatusStore.Get | p99 | 574ms | 499ms | -75ms | -13.08
| UserStore.Search | p99 | 2.085s | 1.817s | -268ms | -12.85
| ChannelStore.GetChannelsByUser | p99 | 954ms | 842ms | -112ms | -11.73
| ThreadStore.GetThreadForUser | p99 | 2.054s | 1.813s | -241ms | -11.73
| ProductNoticesStore.View | p99 | 545ms | 482ms | -63ms | -11.56
| ChannelStore.GetChannelUnread | p99 | 979ms | 868ms | -111ms | -11.34
| PostStore.Get | p99 | 2.221s | 1.983s | -238ms | -10.72
| PostStore.GetPosts | p99 | 853ms | 763ms | -90ms | -10.56
| TeamStore.GetTeamsForUser | p99 | 729ms | 654ms | -75ms | -10.29
| ChannelStore.GetTeamChannels | p99 | 977ms | 883ms | -94ms | -9.62
| SessionStore.GetLRUSessions | p99 | 895ms | 811ms | -84ms | -9.39
| UserStore.Save | p99 | 432ms | 395ms | -37ms | -8.56
| ChannelStore.GetMemberCount | p99 | 2.28s | 2.092s | -188ms | -8.25
| ChannelStore.GetGuestCount | p99 | 1.058s | 971ms | -87ms | -8.22
| ChannelStore.IncrementMentionCount | p99 | 87ms | 80ms | -7ms | -8.04
| UserStore.GetByUsername | p99 | 981ms | 903ms | -78ms | -7.95
| ChannelStore.UpdateLastViewedAt | p99 | 203ms | 187ms | -16ms | -7.86
| UserStore.GetProfileByIds | p99 | 908ms | 837ms | -71ms | -7.82
| SessionStore.UpdateLastActivityAt | p99 | 90ms | 83ms | -7ms | -7.77
| ChannelStore.GetMember | p99 | 207ms | 192ms | -15ms | -7.25
| JobStore.Get | p99 | 2.017s | 1.872s | -145ms | -7.19
| ChannelStore.GetAllChannelMembersForUser | p99 | 733ms | 681ms | -52ms | -7.09
| PostAcknowledgementStore.GetForPosts | p99 | 2.288s | 2.129s | -159ms | -6.95
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 916ms | 854ms | -62ms | -6.77
| UserStore.UpdateLastLogin | p99 | 90ms | 84ms | -6ms | -6.64
| PostPriorityStore.GetForPosts | p99 | 2.307s | 2.157s | -150ms | -6.50
| StatusStore.UpdateExpiredDNDStatuses | p99 | 94ms | 88ms | -6ms | -6.40
| AuditStore.Save | p99 | 94ms | 88ms | -6ms | -6.37
| ThreadStore.MarkAsRead | p99 | 95ms | 89ms | -6ms | -6.34
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 80ms | 75ms | -5ms | -6.26
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 977ms | 917ms | -60ms | -6.14
| ThreadStore.GetTotalThreads | p99 | 948ms | 890ms | -58ms | -6.12
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 967ms | 908ms | -59ms | -6.10
| JobStore.GetAllByStatus | p99 | 1.389s | 1.306s | -83ms | -5.98
| EmojiStore.GetMultipleByName | p99 | 489ms | 460ms | -29ms | -5.93
| ThreadStore.GetTotalUnreadThreads | p99 | 928ms | 873ms | -55ms | -5.92
| ThreadStore.GetTotalUnreadMentions | p99 | 947ms | 895ms | -52ms | -5.49
| UserStore.UpdateFailedPasswordAttempts | p99 | 92ms | 87ms | -5ms | -5.45
| GroupStore.GetByName | p99 | 625ms | 591ms | -34ms | -5.44
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 2.254s | 2.132s | -122ms | -5.41
| UserStore.GetAllProfiles | p99 | 857ms | 811ms | -46ms | -5.36
| PostStore.GetPostIdBeforeTime | p99 | 95ms | 90ms | -5ms | -5.26
| StatusStore.UpdateLastActivityAt | p99 | 99ms | 94ms | -5ms | -5.04
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 993ms | 945ms | -48ms | -4.83
| PostStore.Save | p99 | 254ms | 242ms | -12ms | -4.72
| FileInfoStore.Get | p99 | 890ms | 850ms | -40ms | -4.50
| ThreadStore.MaintainMembership | p99 | 222ms | 213ms | -9ms | -4.05
| ChannelStore.GetPinnedPostCount | p99 | 990ms | 950ms | -40ms | -4.04
| PreferenceStore.GetAll | p99 | 997ms | 959ms | -38ms | -3.81
| PreferenceStore.Save | p99 | 236ms | 227ms | -9ms | -3.81
| UserStore.GetProfilesByUsernames | p99 | 919ms | 886ms | -33ms | -3.59
| PostStore.GetPostIdAfterTime | p99 | 84ms | 81ms | -3ms | -3.58
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 839ms | 811ms | -28ms | -3.34
| PostStore.GetPostsBefore | p99 | 1s | 968ms | -32ms | -3.20
| SessionStore.Get | p99 | 916ms | 887ms | -29ms | -3.17
| SessionStore.GetSessionsExpired | p99 | 489ms | 475ms | -14ms | -2.86
| ChannelStore.GetByName | p99 | 911ms | 885ms | -26ms | -2.85
| UserStore.AutocompleteUsersInChannel | p99 | 2.47s | 2.4s | -70ms | -2.83
| ChannelStore.GetMemberLastViewedAt | p99 | 858ms | 834ms | -24ms | -2.80
| UserTermsOfServiceStore.GetByUser | p99 | 944ms | 918ms | -26ms | -2.75
| SystemStore.GetByName | p99 | 77ms | 75ms | -2ms | -2.61
| SessionStore.Save | p99 | 830ms | 809ms | -21ms | -2.53
| ChannelStore.GetFileCount | p99 | 817ms | 798ms | -19ms | -2.33
| TeamStore.GetAllPage | p99 | 904ms | 883ms | -21ms | -2.32
| UserStore.IsEmpty | p99 | 496ms | 485ms | -11ms | -2.22
| UserStore.GetUnreadCount | p99 | 969ms | 948ms | -21ms | -2.17
| TeamStore.GetTeamsByUserId | p99 | 922ms | 905ms | -17ms | -1.84
| ChannelStore.Autocomplete | p99 | 10s | 9.824s | -176ms | -1.76
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 922ms | 906ms | -16ms | -1.74
| ChannelStore.SaveMember | p99 | 2.52s | 2.484s | -36ms | -1.43
| UserStore.GetForLogin | p99 | 830ms | 819ms | -11ms | -1.33
| ChannelStore.GetMembersForUserWithPagination | p99 | 2.162s | 2.14s | -22ms | -1.02
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 495ms | 490ms | -5ms | -1.01
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteEmojis | avg | 18ms | 110ms | 92ms | 512.06
| getChannelMembers | avg | 23ms | 130ms | 107ms | 468.14
| getPrevTrialLicense | avg | 82ms | 318ms | 236ms | 287.84
| createCategoryForTeamForUser | avg | 87ms | 281ms | 194ms | 222.43
| updateReadStateAllThreadsByUser | avg | 4ms | 12ms | 8ms | 196.46
| getFilteredUsersStats | avg | 153ms | 450ms | 297ms | 193.92
| deleteDraft | avg | 63ms | 129ms | 66ms | 104.35
| getAnalytics | avg | 908ms | 1.16s | 252ms | 27.75
| getGroupsAssociatedToChannelsByTeam | avg | 253ms | 322ms | 69ms | 27.23
| getChannelMembersForUser | avg | 317ms | 391ms | 74ms | 23.31
| followThreadByUser | avg | 358ms | 412ms | 54ms | 15.09
| unfollowThreadByUser | avg | 327ms | 373ms | 46ms | 14.08
| createChannel | avg | 1.781s | 2.01s | 229ms | 12.86
| deletePost | avg | 444ms | 498ms | 54ms | 12.17
| getTeamStats | avg | 657ms | 693ms | 36ms | 5.48
| getDrafts | avg | 317ms | 332ms | 15ms | 4.73
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 25ms | 970ms | 945ms | 3801.56
| getPrevTrialLicense | p99 | 246ms | 2.41s | 2.164s | 881.47
| deleteDraft | p99 | 100ms | 960ms | 860ms | 864.32
| updateReadStateAllThreadsByUser | p99 | 10ms | 48ms | 38ms | 385.79
| autocompleteEmojis | p99 | 97ms | 247ms | 150ms | 154.62
| getGroups | p99 | 995ms | 2.395s | 1.4s | 140.70
| getChannelMembersForUser | p99 | 970ms | 2.305s | 1.335s | 137.63
| getFilteredUsersStats | p99 | 493ms | 990ms | 497ms | 100.89
| createChannel | p99 | 4.887s | 8.8s | 3.913s | 80.06
| unfollowThreadByUser | p99 | 2.437s | 2.55s | 113ms | 4.64
| getTeamMember | p99 | 242ms | 247ms | 5ms | 2.06
| createCategoryForTeamForUser | p99 | 490ms | 498ms | 8ms | 1.63
| getAnalytics | p99 | 2.455s | 2.485s | 30ms | 1.22
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 18ms | 0s | -18ms | -102.44
| getClientLicense | avg | 2ms | 0s | -2ms | -101.97
| getEnvironmentConfig | avg | 21ms | 0s | -21ms | -97.84
| getRolesByNames | avg | 167ms | 35ms | -132ms | -78.96
| upsertDraft | avg | 168ms | 36ms | -132ms | -78.75
| logout | avg | 497ms | 247ms | -250ms | -50.31
| getJobsByType | avg | 249ms | 129ms | -120ms | -48.26
| updateCategoriesForTeamForUser | avg | 903ms | 572ms | -331ms | -36.65
| getGroups | avg | 655ms | 480ms | -175ms | -26.73
| getTeamMember | avg | 17ms | 13ms | -4ms | -23.78
| patchPost | avg | 6.934s | 5.56s | -1.374s | -19.82
| getProductNotices | avg | 663ms | 544ms | -119ms | -17.94
| getChannelUnread | avg | 135ms | 111ms | -24ms | -17.73
| getUsersByIds | avg | 12ms | 10ms | -2ms | -16.92
| getPublicChannelsForTeam | avg | 187ms | 156ms | -31ms | -16.57
| createDirectChannel | avg | 1.235s | 1.064s | -171ms | -13.85
| removeUserCustomStatus | avg | 334ms | 288ms | -46ms | -13.76
| setPostReminder | avg | 552ms | 483ms | -69ms | -12.51
| saveReaction | avg | 459ms | 403ms | -56ms | -12.21
| searchPostsInTeam | avg | 512ms | 450ms | -62ms | -12.11
| getPostsForChannel | avg | 1.311s | 1.154s | -157ms | -11.97
| getPostThread | avg | 826ms | 730ms | -96ms | -11.62
| searchGroupChannels | avg | 164ms | 146ms | -18ms | -11.00
| updateReadStateThreadByUser | avg | 1.095s | 976ms | -119ms | -10.87
| getChannelMembersForTeamForUser | avg | 140ms | 125ms | -15ms | -10.68
| getProfileImage | avg | 97ms | 87ms | -10ms | -10.27
| getChannelsForUser | avg | 127ms | 114ms | -13ms | -10.24
| viewChannel | avg | 290ms | 261ms | -29ms | -10.00
| getChannel | avg | 382ms | 344ms | -38ms | -9.95
| getCategoriesForTeamForUser | avg | 268ms | 242ms | -26ms | -9.69
| getChannelStats | avg | 116ms | 105ms | -11ms | -9.45
| getFilePreview | avg | 152ms | 138ms | -14ms | -9.24
| getThreadsForUser | avg | 164ms | 149ms | -15ms | -9.12
| updatePreferences | avg | 33ms | 30ms | -3ms | -8.96
| createUser | avg | 445ms | 406ms | -39ms | -8.76
| login | avg | 481ms | 439ms | -42ms | -8.73
| getTeamMembersForUser | avg | 92ms | 84ms | -8ms | -8.73
| getPostsForChannelAroundLastUnread | avg | 495ms | 452ms | -43ms | -8.69
| autocompleteChannelsForTeamForSearch | avg | 584ms | 535ms | -49ms | -8.40
| getChannelsForTeamForUser | avg | 146ms | 134ms | -12ms | -8.20
| autocompleteUsers | avg | 579ms | 532ms | -47ms | -8.12
| getTeamsUnreadForUser | avg | 185ms | 170ms | -15ms | -8.12
| searchAllChannels | avg | 3.563s | 3.282s | -281ms | -7.89
| getPreferences | avg | 161ms | 149ms | -12ms | -7.45
| getUsersByNames | avg | 113ms | 105ms | -8ms | -7.08
| getFileThumbnail | avg | 145ms | 135ms | -10ms | -6.88
| uploadFileStream | avg | 458ms | 427ms | -31ms | -6.77
| searchUsers | avg | 362ms | 339ms | -23ms | -6.36
| addChannelMember | avg | 2.053s | 1.946s | -107ms | -5.21
| addTeamMember | avg | 3.629s | 3.44s | -189ms | -5.21
| createPost | avg | 3.102s | 2.964s | -138ms | -4.45
| getChannelMember | avg | 160ms | 154ms | -6ms | -3.75
| getTeamsForUser | avg | 118ms | 114ms | -4ms | -3.39
| getUser | avg | 154ms | 149ms | -5ms | -3.24
| getAllTeams | avg | 119ms | 116ms | -3ms | -2.51
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getEnvironmentConfig | p99 | 25ms | 0s | -25ms | -100.54
| channelMemberCountsByGroup | p99 | 98ms | 0s | -98ms | -100.00
| upsertDraft | p99 | 2.38s | 243ms | -2.137s | -89.79
| getJobsByType | p99 | 6.252s | 899ms | -5.353s | -85.61
| getRolesByNames | p99 | 2.388s | 474ms | -1.914s | -80.17
| logout | p99 | 2.39s | 496ms | -1.894s | -79.25
| getClientLicense | p99 | 23ms | 5ms | -18ms | -76.60
| getPublicChannelsForTeam | p99 | 1.74s | 879ms | -861ms | -49.48
| followThreadByUser | p99 | 4.45s | 2.29s | -2.16s | -48.54
| removeUserCustomStatus | p99 | 1.905s | 996ms | -909ms | -47.72
| deletePost | p99 | 4.45s | 2.372s | -2.078s | -46.70
| autocompleteChannelsForTeamForSearch | p99 | 3.998s | 2.438s | -1.56s | -39.02
| searchGroupChannels | p99 | 1.561s | 1.07s | -491ms | -31.46
| login | p99 | 3.373s | 2.527s | -846ms | -25.08
| updateReadStateThreadByUser | p99 | 6.617s | 4.973s | -1.644s | -24.85
| createDirectChannel | p99 | 5.951s | 4.546s | -1.405s | -23.61
| getChannelMembersForTeamForUser | p99 | 1.232s | 967ms | -265ms | -21.52
| saveReaction | p99 | 3.093s | 2.445s | -648ms | -20.95
| getChannelsForTeamForUser | p99 | 1.192s | 983ms | -209ms | -17.53
| getThreadsForUser | p99 | 1.786s | 1.478s | -308ms | -17.24
| getChannelUnread | p99 | 1.149s | 964ms | -185ms | -16.10
| uploadFileStream | p99 | 2.019s | 1.75s | -269ms | -13.32
| updateCategoriesForTeamForUser | p99 | 4.613s | 4s | -613ms | -13.29
| getUserStatusesByIds | p99 | 23ms | 20ms | -3ms | -12.92
| searchUsers | p99 | 2.082s | 1.843s | -239ms | -11.48
| getUsersByIds | p99 | 276ms | 246ms | -30ms | -10.86
| getTeamsUnreadForUser | p99 | 2.024s | 1.815s | -209ms | -10.33
| getPostsForChannelAroundLastUnread | p99 | 3.993s | 3.585s | -408ms | -10.22
| getChannelsForUser | p99 | 956ms | 869ms | -87ms | -9.10
| getChannelStats | p99 | 1.89s | 1.718s | -172ms | -9.10
| getPreferences | p99 | 1.054s | 972ms | -82ms | -7.78
| getTeamMembersForUser | p99 | 820ms | 758ms | -62ms | -7.56
| getCategoriesForTeamForUser | p99 | 2.256s | 2.135s | -121ms | -5.36
| getPostThread | p99 | 4.911s | 4.663s | -248ms | -5.05
| viewChannel | p99 | 2.296s | 2.183s | -113ms | -4.92
| searchPostsInTeam | p99 | 4.777s | 4.563s | -214ms | -4.48
| getChannelMember | p99 | 1.626s | 1.558s | -68ms | -4.18
| getFilePreview | p99 | 930ms | 892ms | -38ms | -4.09
| getUsers | p99 | 728ms | 702ms | -26ms | -3.57
| autocompleteUsers | p99 | 2.445s | 2.362s | -83ms | -3.39
| getUsersByNames | p99 | 926ms | 895ms | -31ms | -3.35
| getFileThumbnail | p99 | 943ms | 913ms | -30ms | -3.18
| createUser | p99 | 2.419s | 2.345s | -74ms | -3.06
| getChannel | p99 | 2.468s | 2.399s | -69ms | -2.80
| getProfileImage | p99 | 489ms | 476ms | -13ms | -2.66
| getTeamsForUser | p99 | 924ms | 904ms | -20ms | -2.17
| getClientConfig | p99 | 444ms | 436ms | -8ms | -1.80
| searchAllChannels | p99 | 10s | 9.825s | -175ms | -1.75
| getAllTeams | p99 | 937ms | 924ms | -13ms | -1.39
| getUser | p99 | 996ms | 984ms | -12ms | -1.20
| updatePreferences | p99 | 250ms | 247ms | -3ms | -1.20
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 9ms| 8ms | -1ms | -11.302
| |  P99| 94ms| 88ms | -6ms | -6.368
| BotStore.Get |  Avg| 120ms| 147ms | 27ms | 22.476
| |  P99| 875ms| 875ms | 0s | 0.000
| BotStore.Save |  Avg| 3ms| 0s | -3ms | -89.636
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 739ms| 679ms | -60ms | -8.122
| |  P99| 3.011s| 2.458s | -553ms | -18.368
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 81ms| 80ms | -1ms | -1.235
| ChannelStore.AnalyticsTypeCount |  Avg| 100ms| 238ms | 138ms | 137.499
| |  P99| 475ms| 940ms | 465ms | 97.894
| ChannelStore.Autocomplete |  Avg| 3.557s| 3.277s | -280ms | -7.872
| |  P99| 10s| 9.824s | -176ms | -1.760
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 584ms| 535ms | -49ms | -8.397
| |  P99| 3.998s| 2.438s | -1.56s | -39.023
| ChannelStore.CreateDirectChannel |  Avg| 446ms| 423ms | -23ms | -5.158
| |  P99| 3.344s| 2.486s | -858ms | -25.659
| ChannelStore.CreateInitialSidebarCategories |  Avg| 128ms| 123ms | -5ms | -3.913
| |  P99| 898ms| 904ms | 6ms | 0.668
| ChannelStore.CreateSidebarCategory |  Avg| 58ms| 202ms | 144ms | 247.945
| |  P99| 244ms| 249ms | 5ms | 2.049
| ChannelStore.Get |  Avg| 181ms| 170ms | -11ms | -6.075
| |  P99| 1.689s| 1.441s | -248ms | -14.682
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 148ms| 143ms | -5ms | -3.370
| |  P99| 922ms| 906ms | -16ms | -1.735
| ChannelStore.GetAllChannelMembersForUser |  Avg| 78ms| 75ms | -3ms | -3.847
| |  P99| 733ms| 681ms | -52ms | -7.093
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 153ms| 152ms | -1ms | -0.655
| |  P99| 985ms| 1.034s | 49ms | 4.973
| ChannelStore.GetByName |  Avg| 105ms| 99ms | -6ms | -5.703
| |  P99| 911ms| 885ms | -26ms | -2.854
| ChannelStore.GetChannelUnread |  Avg| 126ms| 100ms | -26ms | -20.694
| |  P99| 979ms| 868ms | -111ms | -11.341
| ChannelStore.GetChannels |  Avg| 142ms| 129ms | -13ms | -9.153
| |  P99| 1.168s| 976ms | -192ms | -16.435
| ChannelStore.GetChannelsByIds |  Avg| 159ms| 170ms | 11ms | 6.918
| |  P99| 488ms| 488ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 126ms| 113ms | -13ms | -10.279
| |  P99| 954ms| 842ms | -112ms | -11.734
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 125ms| 114ms | -11ms | -8.794
| |  P99| 993ms| 945ms | -48ms | -4.833
| ChannelStore.GetFileCount |  Avg| 102ms| 94ms | -8ms | -7.822
| |  P99| 817ms| 798ms | -19ms | -2.326
| ChannelStore.GetGuestCount |  Avg| 145ms| 134ms | -11ms | -7.566
| |  P99| 1.058s| 971ms | -87ms | -8.221
| ChannelStore.GetMember |  Avg| 13ms| 11ms | -2ms | -15.980
| |  P99| 207ms| 192ms | -15ms | -7.248
| ChannelStore.GetMemberCount |  Avg| 508ms| 452ms | -56ms | -11.020
| |  P99| 2.28s| 2.092s | -188ms | -8.246
| ChannelStore.GetMemberCountsByGroup |  Avg| 17ms| 0s | -17ms | -98.888
| |  P99| 98ms| 0s | -98ms | -100.000
| ChannelStore.GetMemberForPost |  Avg| 159ms| 145ms | -14ms | -8.815
| |  P99| 1.574s| 1.246s | -328ms | -20.843
| ChannelStore.GetMemberLastViewedAt |  Avg| 97ms| 90ms | -7ms | -7.181
| |  P99| 858ms| 834ms | -24ms | -2.796
| ChannelStore.GetMembers |  Avg| 21ms| 128ms | 107ms | 502.397
| |  P99| 25ms| 970ms | 945ms | 3801.559
| ChannelStore.GetMembersForUser |  Avg| 139ms| 124ms | -15ms | -10.791
| |  P99| 1.227s| 964ms | -263ms | -21.427
| ChannelStore.GetMembersForUserWithPagination |  Avg| 255ms| 316ms | 61ms | 23.935
| |  P99| 2.162s| 2.14s | -22ms | -1.017
| ChannelStore.GetPinnedPostCount |  Avg| 132ms| 118ms | -14ms | -10.602
| |  P99| 990ms| 950ms | -40ms | -4.041
| ChannelStore.GetPublicChannelsForTeam |  Avg| 185ms| 154ms | -31ms | -16.733
| |  P99| 1.74s| 879ms | -861ms | -49.482
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 267ms| 242ms | -25ms | -9.346
| |  P99| 2.254s| 2.132s | -122ms | -5.413
| ChannelStore.GetSidebarCategory |  Avg| 170ms| 122ms | -48ms | -28.234
| |  P99| 1.6s| 630ms | -970ms | -60.615
| ChannelStore.GetTeamChannels |  Avg| 252ms| 203ms | -49ms | -19.445
| |  P99| 977ms| 883ms | -94ms | -9.616
| ChannelStore.IncrementMentionCount |  Avg| 7ms| 6ms | -1ms | -15.140
| |  P99| 87ms| 80ms | -7ms | -8.044
| ChannelStore.Save |  Avg| 163ms| 212ms | 49ms | 30.064
| |  P99| 961ms| 1.915s | 954ms | 99.241
| ChannelStore.SaveMember |  Avg| 449ms| 422ms | -27ms | -6.008
| |  P99| 2.52s| 2.484s | -36ms | -1.428
| ChannelStore.SearchGroupChannels |  Avg| 163ms| 146ms | -17ms | -10.418
| |  P99| 1.561s| 1.07s | -491ms | -31.460
| ChannelStore.UpdateLastViewedAt |  Avg| 17ms| 15ms | -2ms | -11.680
| |  P99| 203ms| 187ms | -16ms | -7.864
| ChannelStore.UpdateSidebarCategories |  Avg| 394ms| 253ms | -141ms | -35.819
| |  P99| 2.268s| 1.87s | -398ms | -17.552
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 80ms| 75ms | -5ms | -6.259
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 9ms| 8ms | -1ms | -11.184
| |  P99| 83ms| 69ms | -14ms | -16.787
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.020
| ComplianceStore.MessageExport |  Avg| 133ms| 94ms | -39ms | -29.280
| |  P99| 1.65s| 1.325s | -325ms | -19.697
| DraftStore.Delete |  Avg| 3ms| 21ms | 18ms | 703.634
| |  P99| 5ms| 25ms | 20ms | 404.040
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 20ms| 18ms | -2ms | -9.977
| |  P99| 97ms| 224ms | 127ms | 130.592
| DraftStore.Get |  Avg| 59ms| 29ms | -30ms | -51.084
| |  P99| 100ms| 241ms | 141ms | 141.709
| DraftStore.GetDraftsForUser |  Avg| 229ms| 270ms | 41ms | 17.872
| |  P99| 496ms| 495ms | -1ms | -0.202
| DraftStore.Upsert |  Avg| 5ms| 3ms | -2ms | -41.028
| |  P99| 10ms| 5ms | -5ms | -50.727
| EmojiStore.GetByName |  Avg| 148ms| 126ms | -22ms | -14.911
| |  P99| 1.314s| 942ms | -372ms | -28.319
| EmojiStore.GetMultipleByName |  Avg| 83ms| 115ms | 32ms | 38.357
| |  P99| 489ms| 460ms | -29ms | -5.933
| EmojiStore.Search |  Avg| 18ms| 110ms | 92ms | 513.552
| |  P99| 97ms| 247ms | 150ms | 154.621
| FileInfoStore.AttachToPost |  Avg| 11ms| 12ms | 1ms | 8.697
| |  P99| 137ms| 114ms | -23ms | -16.792
| FileInfoStore.Get |  Avg| 101ms| 92ms | -9ms | -8.910
| |  P99| 890ms| 850ms | -40ms | -4.495
| FileInfoStore.GetForPost |  Avg| 149ms| 130ms | -19ms | -12.788
| |  P99| 1.59s| 1.013s | -577ms | -36.293
| FileInfoStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 91ms| 96ms | 5ms | 5.465
| FileInfoStore.SetContent |  Avg| 15ms| 18ms | 3ms | 19.503
| |  P99| 170ms| 199ms | 29ms | 17.049
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 103ms| 99ms | -4ms | -3.895
| |  P99| 839ms| 811ms | -28ms | -3.339
| GroupStore.GetByName |  Avg| 81ms| 73ms | -8ms | -9.917
| |  P99| 625ms| 591ms | -34ms | -5.441
| GroupStore.GetGroups |  Avg| 140ms| 128ms | -12ms | -8.591
| |  P99| 1.299s| 984ms | -315ms | -24.245
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 253ms| 230ms | -23ms | -9.080
| |  P99| 495ms| 490ms | -5ms | -1.010
| JobStore.Get |  Avg| 164ms| 160ms | -4ms | -2.445
| |  P99| 2.017s| 1.872s | -145ms | -7.189
| JobStore.GetAllByStatus |  Avg| 140ms| 133ms | -7ms | -4.988
| |  P99| 1.389s| 1.306s | -83ms | -5.976
| JobStore.GetAllByTypePage |  Avg| 245ms| 128ms | -117ms | -47.724
| |  P99| 6.202s| 899ms | -5.303s | -85.498
| JobStore.GetCountByStatusAndType |  Avg| 119ms| 136ms | 17ms | 14.320
| |  P99| 1.285s| 883ms | -402ms | -31.284
| JobStore.GetNewestJobByStatusesAndType |  Avg| 114ms| 111ms | -3ms | -2.643
| |  P99| 913ms| 1.795s | 882ms | 96.569
| JobStore.Save |  Avg| 11ms| 7ms | -4ms | -37.601
| |  P99| 89ms| 66ms | -23ms | -25.940
| JobStore.UpdateOptimistically |  Avg| 14ms| 10ms | -4ms | -29.077
| |  P99| 174ms| 95ms | -79ms | -45.484
| JobStore.UpdateStatus |  Avg| 8ms| 6ms | -2ms | -26.505
| |  P99| 66ms| 66ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 8ms| 6ms | -2ms | -23.542
| |  P99| 65ms| 83ms | 18ms | 27.691
| LicenseStore.GetAll |  Avg| 85ms| 234ms | 149ms | 174.287
| |  P99| 246ms| 2.365s | 2.119s | 863.133
| LinkMetadataStore.Get |  Avg| 131ms| 122ms | -9ms | -6.846
| |  P99| 1.332s| 979ms | -353ms | -26.499
| LinkMetadataStore.Save |  Avg| 15ms| 9ms | -6ms | -38.949
| |  P99| 183ms| 97ms | -86ms | -46.891
| PluginStore.Delete |  Avg| 5ms| 4ms | -1ms | -19.561
| |  P99| 65ms| 51ms | -14ms | -21.583
| PluginStore.Get |  Avg| 102ms| 219ms | 117ms | 115.028
| |  P99| 470ms| 491ms | 21ms | 4.468
| PluginStore.List |  Avg| 201ms| 116ms | -85ms | -42.318
| |  P99| 1.72s| 917ms | -803ms | -46.693
| PluginStore.SetWithOptions |  Avg| 12ms| 10ms | -2ms | -16.488
| |  P99| 158ms| 104ms | -54ms | -34.101
| PostAcknowledgementStore.GetForPost |  Avg| 116ms| 108ms | -8ms | -6.903
| |  P99| 832ms| 1.06s | 228ms | 27.396
| PostAcknowledgementStore.GetForPosts |  Avg| 215ms| 188ms | -27ms | -12.579
| |  P99| 2.288s| 2.129s | -159ms | -6.950
| PostPersistentNotificationStore.DeleteExpired |  Avg| 8ms| 6ms | -2ms | -25.592
| |  P99| 187ms| 90ms | -97ms | -51.870
| PostPersistentNotificationStore.Get |  Avg| 7ms| 5ms | -2ms | -27.915
| |  P99| 47ms| 78ms | 31ms | 65.957
| PostPersistentNotificationStore.GetSingle |  Avg| 146ms| 133ms | -13ms | -8.921
| |  P99| 1.254s| 969ms | -285ms | -22.718
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 35ms| 31ms | -4ms | -11.305
| |  P99| 98ms| 98ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 140ms| 110ms | -30ms | -21.480
| |  P99| 1s| 762ms | -238ms | -23.800
| PostPriorityStore.GetForPosts |  Avg| 221ms| 194ms | -27ms | -12.206
| |  P99| 2.307s| 2.157s | -150ms | -6.501
| PostStore.AnalyticsPostCount |  Avg| 256ms| 2.253s | 1.997s | 780.659
| |  P99| 498ms| 4.925s | 4.427s | 889.601
| PostStore.Delete |  Avg| 149ms| 165ms | 16ms | 10.708
| |  P99| 890ms| 486ms | -404ms | -45.395
| PostStore.Get |  Avg| 243ms| 212ms | -31ms | -12.745
| |  P99| 2.221s| 1.983s | -238ms | -10.715
| PostStore.GetEtag |  Avg| 151ms| 140ms | -11ms | -7.277
| |  P99| 1.178s| 1.019s | -159ms | -13.499
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 84ms| 81ms | -3ms | -3.576
| PostStore.GetPostIdBeforeTime |  Avg| 9ms| 8ms | -1ms | -10.937
| |  P99| 95ms| 90ms | -5ms | -5.262
| PostStore.GetPostReminderMetadata |  Avg| 113ms| 67ms | -46ms | -40.833
| |  P99| 795ms| 433ms | -362ms | -45.537
| PostStore.GetPostReminders |  Avg| 20ms| 7ms | -13ms | -65.138
| |  P99| 437ms| 44ms | -393ms | -89.829
| PostStore.GetPosts |  Avg| 98ms| 89ms | -9ms | -9.173
| |  P99| 853ms| 763ms | -90ms | -10.556
| PostStore.GetPostsAfter |  Avg| 116ms| 97ms | -19ms | -16.422
| |  P99| 1.364s| 878ms | -486ms | -35.637
| PostStore.GetPostsBefore |  Avg| 139ms| 127ms | -12ms | -8.628
| |  P99| 1s| 968ms | -32ms | -3.201
| PostStore.GetPostsByIds |  Avg| 135ms| 190ms | 55ms | 40.750
| |  P99| 248ms| 495ms | 247ms | 99.570
| PostStore.GetPostsByThread |  Avg| 141ms| 124ms | -17ms | -12.019
| |  P99| 1.302s| 987ms | -315ms | -24.188
| PostStore.GetPostsSince |  Avg| 182ms| 164ms | -18ms | -9.883
| |  P99| 1.515s| 1.068s | -447ms | -29.506
| PostStore.GetSingle |  Avg| 129ms| 119ms | -10ms | -7.775
| |  P99| 1.277s| 976ms | -301ms | -23.574
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 28ms| 25ms | -3ms | -10.722
| |  P99| 254ms| 242ms | -12ms | -4.722
| PostStore.SearchPostsForUser |  Avg| 233ms| 194ms | -39ms | -16.719
| |  P99| 1.837s| 1.466s | -371ms | -20.197
| PostStore.SetPostReminder |  Avg| 16ms| 13ms | -3ms | -18.272
| |  P99| 220ms| 93ms | -127ms | -57.726
| PostStore.Update |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 232ms| 242ms | 10ms | 4.318
| PreferenceStore.DeleteCategoryAndName |  Avg| 17ms| 19ms | 2ms | 11.454
| |  P99| 96ms| 224ms | 128ms | 132.873
| PreferenceStore.Get |  Avg| 134ms| 122ms | -12ms | -8.923
| |  P99| 1.118s| 964ms | -154ms | -13.776
| PreferenceStore.GetAll |  Avg| 158ms| 146ms | -12ms | -7.612
| |  P99| 997ms| 959ms | -38ms | -3.812
| PreferenceStore.Save |  Avg| 22ms| 20ms | -2ms | -8.935
| |  P99| 236ms| 227ms | -9ms | -3.810
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 57ms | 55ms | 3253.179
| |  P99| 5ms| 247ms | 242ms | 4887.154
| ProductNoticesStore.GetViews |  Avg| 458ms| 437ms | -21ms | -4.584
| |  P99| 2.455s| 2.44s | -15ms | -0.611
| ProductNoticesStore.View |  Avg| 61ms| 56ms | -5ms | -8.256
| |  P99| 545ms| 482ms | -63ms | -11.560
| ReactionStore.GetForPost |  Avg| 151ms| 119ms | -32ms | -21.151
| |  P99| 1.233s| 909ms | -324ms | -26.277
| RetentionPolicyStore.GetAll |  Avg| 148ms| 0s | -148ms | -99.873
| |  P99| 495ms| 0s | -495ms | -100.000
| RetentionPolicyStore.GetCount |  Avg| 146ms| 0s | -146ms | -100.063
| |  P99| 249ms| 0s | -249ms | -100.201
| RoleStore.ChannelHigherScopedPermissions |  Avg| 90ms| 134ms | 44ms | 48.969
| |  P99| 498ms| 1.585s | 1.087s | 218.488
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 114ms| 107ms | -7ms | -6.130
| |  P99| 916ms| 887ms | -29ms | -3.166
| SessionStore.GetLRUSessions |  Avg| 104ms| 95ms | -9ms | -8.695
| |  P99| 895ms| 811ms | -84ms | -9.389
| SessionStore.GetSessionsExpired |  Avg| 149ms| 92ms | -57ms | -38.258
| |  P99| 489ms| 475ms | -14ms | -2.864
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 115ms| 108ms | -7ms | -6.112
| |  P99| 967ms| 908ms | -59ms | -6.099
| SessionStore.Remove |  Avg| 9ms| 7ms | -2ms | -22.975
| |  P99| 47ms| 25ms | -22ms | -46.554
| SessionStore.Save |  Avg| 103ms| 97ms | -6ms | -5.809
| |  P99| 830ms| 809ms | -21ms | -2.532
| SessionStore.UpdateLastActivityAt |  Avg| 9ms| 8ms | -1ms | -11.174
| |  P99| 90ms| 83ms | -7ms | -7.765
| StatusStore.Get |  Avg| 71ms| 64ms | -7ms | -9.869
| |  P99| 574ms| 499ms | -75ms | -13.077
| StatusStore.GetByIds |  Avg| 156ms| 140ms | -16ms | -10.266
| |  P99| 1.87s| 1.302s | -568ms | -30.374
| StatusStore.SaveOrUpdate |  Avg| 13ms| 12ms | -1ms | -7.451
| |  P99| 188ms| 136ms | -52ms | -27.663
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 14ms| 10ms | -4ms | -29.336
| |  P99| 94ms| 88ms | -6ms | -6.400
| StatusStore.UpdateLastActivityAt |  Avg| 10ms| 9ms | -1ms | -9.557
| |  P99| 99ms| 94ms | -5ms | -5.043
| SystemStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 77ms| 75ms | -2ms | -2.611
| TeamStore.AnalyticsTeamCount |  Avg| 149ms| 333ms | 184ms | 123.602
| |  P99| 970ms| 970ms | 0s | 0.000
| TeamStore.Get |  Avg| 125ms| 116ms | -9ms | -7.228
| |  P99| 1.14s| 968ms | -172ms | -15.090
| TeamStore.GetActiveMemberCount |  Avg| 433ms| 525ms | 92ms | 21.257
| |  P99| 989ms| 2.155s | 1.166s | 117.927
| TeamStore.GetAllPage |  Avg| 112ms| 108ms | -4ms | -3.567
| |  P99| 904ms| 883ms | -21ms | -2.324
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 112ms| 104ms | -8ms | -7.126
| |  P99| 916ms| 854ms | -62ms | -6.767
| TeamStore.GetMany |  Avg| 89ms| 260ms | 171ms | 191.183
| |  P99| 243ms| 975ms | 732ms | 301.538
| TeamStore.GetMember |  Avg| 7ms| 6ms | -1ms | -13.491
| |  P99| 173ms| 144ms | -29ms | -16.752
| TeamStore.GetTeamsByUserId |  Avg| 118ms| 113ms | -5ms | -4.247
| |  P99| 922ms| 905ms | -17ms | -1.843
| TeamStore.GetTeamsForUser |  Avg| 84ms| 77ms | -7ms | -8.371
| |  P99| 729ms| 654ms | -75ms | -10.289
| TeamStore.GetTotalMemberCount |  Avg| 530ms| 432ms | -98ms | -18.496
| |  P99| 2.365s| 981ms | -1.384s | -58.521
| TeamStore.SaveMember |  Avg| 217ms| 209ms | -8ms | -3.692
| |  P99| 965ms| 964ms | -1ms | -0.104
| ThreadStore.Get |  Avg| 144ms| 202ms | 58ms | 40.185
| |  P99| 1.755s| 2.29s | 535ms | 30.484
| ThreadStore.GetMembershipForUser |  Avg| 137ms| 127ms | -10ms | -7.300
| |  P99| 1.235s| 989ms | -246ms | -19.920
| ThreadStore.GetTeamsUnreadForUser |  Avg| 145ms| 131ms | -14ms | -9.636
| |  P99| 1.757s| 1.402s | -355ms | -20.208
| ThreadStore.GetThreadFollowers |  Avg| 146ms| 132ms | -14ms | -9.606
| |  P99| 1.462s| 988ms | -474ms | -32.425
| ThreadStore.GetThreadForUser |  Avg| 207ms| 188ms | -19ms | -9.171
| |  P99| 2.054s| 1.813s | -241ms | -11.734
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 149ms| 135ms | -14ms | -9.379
| |  P99| 1.515s| 995ms | -520ms | -34.319
| ThreadStore.GetThreadsForUser |  Avg| 158ms| 144ms | -14ms | -8.840
| |  P99| 1.454s| 1.088s | -366ms | -25.168
| ThreadStore.GetTotalThreads |  Avg| 112ms| 102ms | -10ms | -8.927
| |  P99| 948ms| 890ms | -58ms | -6.116
| ThreadStore.GetTotalUnreadMentions |  Avg| 112ms| 103ms | -9ms | -8.048
| |  P99| 947ms| 895ms | -52ms | -5.494
| ThreadStore.GetTotalUnreadThreads |  Avg| 111ms| 103ms | -8ms | -7.188
| |  P99| 928ms| 873ms | -55ms | -5.924
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 115ms| 106ms | -9ms | -7.846
| |  P99| 977ms| 917ms | -60ms | -6.144
| ThreadStore.MaintainMembership |  Avg| 19ms| 17ms | -2ms | -10.703
| |  P99| 222ms| 213ms | -9ms | -4.053
| ThreadStore.MarkAllAsReadByChannels |  Avg| 12ms| 11ms | -1ms | -8.324
| |  P99| 153ms| 102ms | -51ms | -33.278
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 11ms | 7ms | 176.698
| |  P99| 10ms| 48ms | 38ms | 385.787
| ThreadStore.MarkAsRead |  Avg| 10ms| 9ms | -1ms | -9.826
| |  P99| 95ms| 89ms | -6ms | -6.341
| ThreadStore.UpdateMembership |  Avg| 12ms| 10ms | -2ms | -17.052
| |  P99| 129ms| 97ms | -32ms | -24.748
| TokenStore.Cleanup |  Avg| 2ms| 3ms | 1ms | 42.114
| |  P99| 10ms| 10ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 121ms| 51ms | -70ms | -58.072
| |  P99| 485ms| 420ms | -65ms | -13.402
| UserStore.AnalyticsActiveCount |  Avg| 596ms| 853ms | 257ms | 43.127
| |  P99| 2.35s| 2.44s | 90ms | 3.830
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 222ms| 115ms | -107ms | -48.100
| |  P99| 975ms| 247ms | -728ms | -74.666
| UserStore.AutocompleteUsersInChannel |  Avg| 680ms| 623ms | -57ms | -8.379
| |  P99| 2.47s| 2.4s | -70ms | -2.834
| UserStore.Count |  Avg| 349ms| 359ms | 10ms | 2.865
| |  P99| 971ms| 981ms | 10ms | 1.030
| UserStore.Get |  Avg| 50ms| 52ms | 2ms | 4.002
| |  P99| 637ms| 657ms | 20ms | 3.141
| UserStore.GetAllProfiles |  Avg| 88ms| 83ms | -5ms | -5.694
| |  P99| 857ms| 811ms | -46ms | -5.365
| UserStore.GetAllProfilesInChannel |  Avg| 1.149s| 1.037s | -112ms | -9.749
| |  P99| 4.164s| 2.486s | -1.678s | -40.294
| UserStore.GetByUsername |  Avg| 143ms| 117ms | -26ms | -18.180
| |  P99| 981ms| 903ms | -78ms | -7.948
| UserStore.GetForLogin |  Avg| 96ms| 91ms | -5ms | -5.207
| |  P99| 830ms| 819ms | -11ms | -1.325
| UserStore.GetMany |  Avg| 156ms| 142ms | -14ms | -8.984
| |  P99| 490ms| 2.095s | 1.605s | 327.273
| UserStore.GetProfileByIds |  Avg| 81ms| 75ms | -6ms | -7.388
| |  P99| 908ms| 837ms | -71ms | -7.821
| UserStore.GetProfilesByUsernames |  Avg| 111ms| 104ms | -7ms | -6.282
| |  P99| 919ms| 886ms | -33ms | -3.591
| UserStore.GetProfilesInChannel |  Avg| 115ms| 164ms | 49ms | 42.744
| |  P99| 480ms| 1.57s | 1.09s | 227.084
| UserStore.GetProfilesNotInChannel |  Avg| 282ms| 120ms | -162ms | -57.443
| |  P99| 2.365s| 486ms | -1.879s | -79.452
| UserStore.GetUnreadCount |  Avg| 118ms| 109ms | -9ms | -7.636
| |  P99| 969ms| 948ms | -21ms | -2.167
| UserStore.IsEmpty |  Avg| 56ms| 50ms | -6ms | -10.739
| |  P99| 496ms| 485ms | -11ms | -2.220
| UserStore.Save |  Avg| 95ms| 92ms | -3ms | -3.167
| |  P99| 432ms| 395ms | -37ms | -8.565
| UserStore.Search |  Avg| 360ms| 334ms | -26ms | -7.217
| |  P99| 2.085s| 1.817s | -268ms | -12.853
| UserStore.Update |  Avg| 15ms| 13ms | -2ms | -13.484
| |  P99| 190ms| 99ms | -91ms | -48.020
| UserStore.UpdateFailedPasswordAttempts |  Avg| 9ms| 8ms | -1ms | -11.241
| |  P99| 92ms| 87ms | -5ms | -5.449
| UserStore.UpdateLastLogin |  Avg| 9ms| 8ms | -1ms | -11.726
| |  P99| 90ms| 84ms | -6ms | -6.640
| UserStore.UpdateUpdateAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 78ms| 79ms | 1ms | 1.283
| UserTermsOfServiceStore.GetByUser |  Avg| 127ms| 121ms | -6ms | -4.710
| |  P99| 944ms| 918ms | -26ms | -2.754
| WebhookStore.GetOutgoingByTeam |  Avg| 148ms| 136ms | -12ms | -8.131
| |  P99| 1.382s| 1.003s | -379ms | -27.426
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 2.053s| 1.946s | -107ms | -5.211
| | P99| 9.56s| 9.553s | -7ms | -0.073
| addTeamMember | Avg| 3.629s| 3.44s | -189ms | -5.207
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 584ms| 535ms | -49ms | -8.395
| | P99| 3.998s| 2.438s | -1.56s | -39.023
| autocompleteEmojis | Avg| 18ms| 110ms | 92ms | 512.064
| | P99| 97ms| 247ms | 150ms | 154.621
| autocompleteUsers | Avg| 579ms| 532ms | -47ms | -8.120
| | P99| 2.445s| 2.362s | -83ms | -3.394
| channelMemberCountsByGroup | Avg| 18ms| 0s | -18ms | -102.443
| | P99| 98ms| 0s | -98ms | -100.000
| createCategoryForTeamForUser | Avg| 87ms| 281ms | 194ms | 222.426
| | P99| 490ms| 498ms | 8ms | 1.633
| createChannel | Avg| 1.781s| 2.01s | 229ms | 12.858
| | P99| 4.887s| 8.8s | 3.913s | 80.062
| createDirectChannel | Avg| 1.235s| 1.064s | -171ms | -13.847
| | P99| 5.951s| 4.546s | -1.405s | -23.611
| createGroupChannel | Avg| 2.534s| 2.517s | -17ms | -0.671
| | P99| 9.455s| 9.536s | 81ms | 0.857
| createPost | Avg| 3.102s| 2.964s | -138ms | -4.448
| | P99| 10s| 10s | 0s | 0.000
| createUser | Avg| 445ms| 406ms | -39ms | -8.756
| | P99| 2.419s| 2.345s | -74ms | -3.060
| deleteDraft | Avg| 63ms| 129ms | 66ms | 104.352
| | P99| 100ms| 960ms | 860ms | 864.322
| deletePost | Avg| 444ms| 498ms | 54ms | 12.168
| | P99| 4.45s| 2.372s | -2.078s | -46.698
| followThreadByUser | Avg| 358ms| 412ms | 54ms | 15.088
| | P99| 4.45s| 2.29s | -2.16s | -48.539
| getAllTeams | Avg| 119ms| 116ms | -3ms | -2.512
| | P99| 937ms| 924ms | -13ms | -1.388
| getAnalytics | Avg| 908ms| 1.16s | 252ms | 27.746
| | P99| 2.455s| 2.485s | 30ms | 1.222
| getCategoriesForTeamForUser | Avg| 268ms| 242ms | -26ms | -9.693
| | P99| 2.256s| 2.135s | -121ms | -5.364
| getChannel | Avg| 382ms| 344ms | -38ms | -9.945
| | P99| 2.468s| 2.399s | -69ms | -2.795
| getChannelMember | Avg| 160ms| 154ms | -6ms | -3.754
| | P99| 1.626s| 1.558s | -68ms | -4.182
| getChannelMembers | Avg| 23ms| 130ms | 107ms | 468.138
| | P99| 25ms| 970ms | 945ms | 3801.559
| getChannelMembersForTeamForUser | Avg| 140ms| 125ms | -15ms | -10.680
| | P99| 1.232s| 967ms | -265ms | -21.518
| getChannelMembersForUser | Avg| 317ms| 391ms | 74ms | 23.313
| | P99| 970ms| 2.305s | 1.335s | 137.626
| getChannelStats | Avg| 116ms| 105ms | -11ms | -9.452
| | P99| 1.89s| 1.718s | -172ms | -9.100
| getChannelUnread | Avg| 135ms| 111ms | -24ms | -17.732
| | P99| 1.149s| 964ms | -185ms | -16.099
| getChannelsForTeamForUser | Avg| 146ms| 134ms | -12ms | -8.201
| | P99| 1.192s| 983ms | -209ms | -17.529
| getChannelsForUser | Avg| 127ms| 114ms | -13ms | -10.244
| | P99| 956ms| 869ms | -87ms | -9.100
| getClientConfig | Avg| 33ms| 32ms | -1ms | -3.070
| | P99| 444ms| 436ms | -8ms | -1.803
| getClientLicense | Avg| 2ms| 0s | -2ms | -101.975
| | P99| 23ms| 5ms | -18ms | -76.597
| getDrafts | Avg| 317ms| 332ms | 15ms | 4.734
| | P99| 498ms| 496ms | -2ms | -0.402
| getEnvironmentConfig | Avg| 21ms| 0s | -21ms | -97.837
| | P99| 25ms| 0s | -25ms | -100.535
| getFilePreview | Avg| 152ms| 138ms | -14ms | -9.237
| | P99| 930ms| 892ms | -38ms | -4.087
| getFileThumbnail | Avg| 145ms| 135ms | -10ms | -6.876
| | P99| 943ms| 913ms | -30ms | -3.183
| getFilteredUsersStats | Avg| 153ms| 450ms | 297ms | 193.925
| | P99| 493ms| 990ms | 497ms | 100.891
| getGroups | Avg| 655ms| 480ms | -175ms | -26.731
| | P99| 995ms| 2.395s | 1.4s | 140.704
| getGroupsAssociatedToChannelsByTeam | Avg| 253ms| 322ms | 69ms | 27.233
| | P99| 495ms| 495ms | 0s | 0.000
| getJobsByType | Avg| 249ms| 129ms | -120ms | -48.257
| | P99| 6.252s| 899ms | -5.353s | -85.615
| getPostThread | Avg| 826ms| 730ms | -96ms | -11.622
| | P99| 4.911s| 4.663s | -248ms | -5.050
| getPostsForChannel | Avg| 1.311s| 1.154s | -157ms | -11.974
| | P99| 10s| 9.958s | -42ms | -0.420
| getPostsForChannelAroundLastUnread | Avg| 495ms| 452ms | -43ms | -8.688
| | P99| 3.993s| 3.585s | -408ms | -10.219
| getPreferences | Avg| 161ms| 149ms | -12ms | -7.449
| | P99| 1.054s| 972ms | -82ms | -7.784
| getPrevTrialLicense | Avg| 82ms| 318ms | 236ms | 287.837
| | P99| 246ms| 2.41s | 2.164s | 881.466
| getProductNotices | Avg| 663ms| 544ms | -119ms | -17.942
| | P99| 2.47s| 2.455s | -15ms | -0.607
| getProfileImage | Avg| 97ms| 87ms | -10ms | -10.274
| | P99| 489ms| 476ms | -13ms | -2.658
| getPublicChannelsForTeam | Avg| 187ms| 156ms | -31ms | -16.573
| | P99| 1.74s| 879ms | -861ms | -49.482
| getRolesByNames | Avg| 167ms| 35ms | -132ms | -78.958
| | P99| 2.388s| 474ms | -1.914s | -80.167
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 17ms| 13ms | -4ms | -23.781
| | P99| 242ms| 247ms | 5ms | 2.065
| getTeamMembersForUser | Avg| 92ms| 84ms | -8ms | -8.727
| | P99| 820ms| 758ms | -62ms | -7.557
| getTeamStats | Avg| 657ms| 693ms | 36ms | 5.478
| | P99| 2.432s| 2.414s | -18ms | -0.740
| getTeamsForUser | Avg| 118ms| 114ms | -4ms | -3.386
| | P99| 924ms| 904ms | -20ms | -2.165
| getTeamsUnreadForUser | Avg| 185ms| 170ms | -15ms | -8.120
| | P99| 2.024s| 1.815s | -209ms | -10.328
| getThreadsForUser | Avg| 164ms| 149ms | -15ms | -9.121
| | P99| 1.786s| 1.478s | -308ms | -17.244
| getUser | Avg| 154ms| 149ms | -5ms | -3.241
| | P99| 996ms| 984ms | -12ms | -1.204
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 1ms | -1ms | -66.299
| | P99| 23ms| 20ms | -3ms | -12.922
| getUsers | Avg| 55ms| 55ms | 0s | 0.000
| | P99| 728ms| 702ms | -26ms | -3.573
| getUsersByIds | Avg| 12ms| 10ms | -2ms | -16.925
| | P99| 276ms| 246ms | -30ms | -10.863
| getUsersByNames | Avg| 113ms| 105ms | -8ms | -7.079
| | P99| 926ms| 895ms | -31ms | -3.347
| getWebappPlugins | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 481ms| 439ms | -42ms | -8.732
| | P99| 3.373s| 2.527s | -846ms | -25.080
| logout | Avg| 497ms| 247ms | -250ms | -50.308
| | P99| 2.39s| 496ms | -1.894s | -79.245
| patchPost | Avg| 6.934s| 5.56s | -1.374s | -19.815
| | P99| 10s| 10s | 0s | 0.000
| removeUserCustomStatus | Avg| 334ms| 288ms | -46ms | -13.756
| | P99| 1.905s| 996ms | -909ms | -47.716
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 459ms| 403ms | -56ms | -12.212
| | P99| 3.093s| 2.445s | -648ms | -20.950
| searchAllChannels | Avg| 3.563s| 3.282s | -281ms | -7.887
| | P99| 10s| 9.825s | -175ms | -1.750
| searchGroupChannels | Avg| 164ms| 146ms | -18ms | -11.003
| | P99| 1.561s| 1.07s | -491ms | -31.460
| searchPostsInTeam | Avg| 512ms| 450ms | -62ms | -12.111
| | P99| 4.777s| 4.563s | -214ms | -4.480
| searchUsers | Avg| 362ms| 339ms | -23ms | -6.358
| | P99| 2.082s| 1.843s | -239ms | -11.478
| setPostReminder | Avg| 552ms| 483ms | -69ms | -12.506
| | P99| 2.425s| 2.43s | 5ms | 0.206
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 327ms| 373ms | 46ms | 14.082
| | P99| 2.437s| 2.55s | 113ms | 4.636
| updateCategoriesForTeamForUser | Avg| 903ms| 572ms | -331ms | -36.650
| | P99| 4.613s| 4s | -613ms | -13.290
| updatePreferences | Avg| 33ms| 30ms | -3ms | -8.959
| | P99| 250ms| 247ms | -3ms | -1.200
| updateReadStateAllThreadsByUser | Avg| 4ms| 12ms | 8ms | 196.459
| | P99| 10ms| 48ms | 38ms | 385.787
| updateReadStateThreadByUser | Avg| 1.095s| 976ms | -119ms | -10.867
| | P99| 6.617s| 4.973s | -1.644s | -24.846
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 458ms| 427ms | -31ms | -6.772
| | P99| 2.019s| 1.75s | -269ms | -13.321
| upsertDraft | Avg| 168ms| 36ms | -132ms | -78.748
| | P99| 2.38s| 243ms | -2.137s | -89.791
| viewChannel | Avg| 290ms| 261ms | -29ms | -9.996
| | P99| 2.296s| 2.183s | -113ms | -4.921
