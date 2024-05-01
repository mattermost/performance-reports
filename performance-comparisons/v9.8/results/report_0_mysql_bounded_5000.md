### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.Search | avg | 5ms | 82ms | 77ms | 1663.15
| ThreadStore.Get | avg | 1ms | 4ms | 3ms | 520.59
| BotStore.Get | avg | 1ms | 6ms | 5ms | 485.15
| JobStore.GetCountByStatusAndType | avg | 1ms | 7ms | 6ms | 472.62
| SessionStore.GetSessionsExpired | avg | 8ms | 36ms | 28ms | 364.90
| TokenStore.Cleanup | avg | 2ms | 6ms | 4ms | 194.51
| CommandWebhookStore.Cleanup | avg | 2ms | 6ms | 4ms | 192.78
| LinkMetadataStore.Get | avg | 1ms | 3ms | 2ms | 190.62
| FileInfoStore.GetForPost | avg | 1ms | 3ms | 2ms | 189.41
| ChannelStore.Get | avg | 3ms | 8ms | 5ms | 182.73
| JobStore.GetNewestJobByStatusesAndType | avg | 3ms | 8ms | 5ms | 175.78
| StatusStore.GetByIds | avg | 1ms | 3ms | 2ms | 169.72
| TeamStore.GetTeamsByUserId | avg | 4ms | 11ms | 7ms | 165.69
| PostStore.GetSingle | avg | 1ms | 3ms | 2ms | 165.01
| UserTermsOfServiceStore.GetByUser | avg | 4ms | 11ms | 7ms | 162.20
| ChannelStore.GetGuestCount | avg | 6ms | 15ms | 9ms | 159.93
| TeamStore.Get | avg | 1ms | 3ms | 2ms | 152.82
| PreferenceStore.GetAll | avg | 6ms | 15ms | 9ms | 150.92
| TeamStore.GetTeamsForUser | avg | 4ms | 10ms | 6ms | 149.25
| TeamStore.GetAllPage | avg | 4ms | 10ms | 6ms | 140.18
| ChannelStore.GetMemberLastViewedAt | avg | 4ms | 9ms | 5ms | 139.18
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 4ms | 9ms | 5ms | 135.36
| JobStore.Get | avg | 2ms | 5ms | 3ms | 132.85
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 14ms | 32ms | 18ms | 131.81
| SessionStore.GetLRUSessions | avg | 5ms | 11ms | 6ms | 130.80
| UserStore.GetForLogin | avg | 5ms | 12ms | 7ms | 129.66
| UserStore.IsEmpty | avg | 3ms | 7ms | 4ms | 128.88
| PostPriorityStore.GetForPosts | avg | 2ms | 5ms | 3ms | 125.68
| PostAcknowledgementStore.GetForPosts | avg | 2ms | 5ms | 3ms | 125.35
| TeamStore.GetChannelUnreadsForAllTeams | avg | 4ms | 9ms | 5ms | 123.52
| ThreadStore.GetThreadsForUser | avg | 2ms | 5ms | 3ms | 123.38
| GroupStore.GetByName | avg | 5ms | 11ms | 6ms | 123.01
| ThreadStore.GetMembershipForUser | avg | 2ms | 4ms | 2ms | 118.25
| PostPersistentNotificationStore.GetSingle | avg | 2ms | 4ms | 2ms | 112.26
| JobStore.GetAllByStatus | avg | 2ms | 4ms | 2ms | 110.70
| PreferenceStore.Get | avg | 2ms | 4ms | 2ms | 110.03
| ChannelStore.GetByName | avg | 5ms | 11ms | 6ms | 109.28
| StatusStore.Get | avg | 4ms | 8ms | 4ms | 109.24
| ThreadStore.GetTotalUnreadThreads | avg | 4ms | 8ms | 4ms | 109.08
| ThreadStore.GetTotalThreads | avg | 4ms | 8ms | 4ms | 108.76
| ThreadStore.GetThreadFollowers | avg | 2ms | 4ms | 2ms | 107.89
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 4ms | 8ms | 4ms | 106.24
| ChannelStore.GetChannelsByUser | avg | 13ms | 27ms | 14ms | 105.60
| ThreadStore.GetTeamsUnreadForUser | avg | 5ms | 10ms | 5ms | 105.20
| PostStore.GetEtag | avg | 4ms | 8ms | 4ms | 101.16
| UserStore.GetProfilesByUsernames | avg | 2ms | 4ms | 2ms | 101.12
| ChannelStore.GetChannels | avg | 3ms | 6ms | 3ms | 99.45
| ChannelStore.GetMembersForUser | avg | 3ms | 6ms | 3ms | 94.22
| ThreadStore.GetTotalUnreadMentions | avg | 4ms | 7ms | 3ms | 84.86
| ChannelStore.SearchGroupChannels | avg | 3ms | 5ms | 2ms | 78.07
| PostStore.GetPosts | avg | 7ms | 12ms | 5ms | 76.10
| UserStore.GetByUsername | avg | 3ms | 5ms | 2ms | 73.39
| SessionStore.Get | avg | 8ms | 14ms | 6ms | 72.30
| GroupStore.GetGroups | avg | 3ms | 5ms | 2ms | 71.77
| ThreadStore.GetThreadForUser | avg | 3ms | 5ms | 2ms | 63.92
| SessionStore.Save | avg | 10ms | 16ms | 6ms | 62.54
| ChannelStore.AnalyticsTypeCount | avg | 3ms | 5ms | 2ms | 60.97
| PostStore.GetPostsBefore | avg | 3ms | 5ms | 2ms | 58.65
| WebhookStore.GetOutgoingByTeam | avg | 3ms | 5ms | 2ms | 57.56
| ChannelStore.SaveMember | avg | 41ms | 63ms | 22ms | 54.23
| UserStore.GetAllProfiles | avg | 6ms | 9ms | 3ms | 52.92
| ChannelStore.GetFileCount | avg | 4ms | 6ms | 2ms | 51.70
| PostStore.Get | avg | 4ms | 6ms | 2ms | 47.32
| ChannelStore.GetPublicChannelsForTeam | avg | 11ms | 16ms | 5ms | 47.09
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 11ms | 16ms | 5ms | 46.44
| ChannelStore.GetMemberCount | avg | 133ms | 186ms | 53ms | 39.87
| ChannelStore.CreateInitialSidebarCategories | avg | 25ms | 32ms | 7ms | 27.62
| ChannelStore.AutocompleteInTeamForSearch | avg | 143ms | 182ms | 39ms | 27.34
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 13ms | 16ms | 3ms | 23.04
| UserStore.GetAllProfilesInChannel | avg | 438ms | 502ms | 64ms | 14.61
| ChannelStore.CreateDirectChannel | avg | 19ms | 21ms | 2ms | 10.57
| UserStore.AutocompleteUsersInChannel | avg | 191ms | 210ms | 19ms | 9.97
| ChannelStore.GetMembersForUserWithPagination | avg | 40ms | 44ms | 4ms | 9.91
| ChannelStore.GetTeamChannels | avg | 32ms | 35ms | 3ms | 9.39
| UserStore.Search | avg | 87ms | 95ms | 8ms | 9.16
| TeamStore.SaveMember | avg | 100ms | 107ms | 7ms | 7.02
| ChannelStore.UpdateSidebarCategories | avg | 51ms | 54ms | 3ms | 5.87
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.Get | p99 | 5ms | 163ms | 158ms | 3191.92
| BotStore.Get | p99 | 5ms | 90ms | 85ms | 1717.17
| FileInfoStore.GetForPost | p99 | 5ms | 58ms | 53ms | 1063.59
| PostStore.GetPostsByThread | p99 | 5ms | 47ms | 42ms | 840.34
| PostStore.GetSingle | p99 | 9ms | 74ms | 65ms | 736.14
| StatusStore.GetByIds | p99 | 18ms | 135ms | 117ms | 637.61
| FileInfoStore.Get | p99 | 6ms | 46ms | 40ms | 615.47
| LinkMetadataStore.Get | p99 | 11ms | 75ms | 64ms | 589.43
| ThreadStore.GetThreadUnreadReplyCount | p99 | 8ms | 53ms | 45ms | 576.19
| JobStore.GetCountByStatusAndType | p99 | 31ms | 200ms | 169ms | 549.59
| SessionStore.GetSessionsExpired | p99 | 48ms | 242ms | 194ms | 400.00
| ChannelStore.AnalyticsTypeCount | p99 | 5ms | 24ms | 19ms | 383.84
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 44ms | 197ms | 153ms | 349.72
| ComplianceStore.MessageExport | p99 | 5ms | 21ms | 16ms | 323.23
| ChannelStore.GetSidebarCategory | p99 | 10ms | 41ms | 31ms | 312.20
| TeamStore.Get | p99 | 22ms | 92ms | 70ms | 311.72
| FileInfoStore.Search | p99 | 25ms | 100ms | 75ms | 305.09
| JobStore.GetAllByStatus | p99 | 25ms | 94ms | 69ms | 278.79
| ReactionStore.GetForPost | p99 | 24ms | 91ms | 67ms | 276.63
| ChannelStore.GetPublicChannelsForTeam | p99 | 51ms | 184ms | 133ms | 259.79
| ThreadStore.GetThreadForUser | p99 | 39ms | 136ms | 97ms | 245.94
| ChannelStore.GetMemberForPost | p99 | 28ms | 94ms | 66ms | 238.67
| UserStore.GetUnreadCount | p99 | 43ms | 141ms | 98ms | 229.58
| GroupStore.GetGroups | p99 | 49ms | 154ms | 105ms | 216.09
| PostStore.Get | p99 | 47ms | 147ms | 100ms | 213.20
| UserStore.GetProfilesByUsernames | p99 | 30ms | 91ms | 61ms | 202.83
| ChannelStore.Get | p99 | 67ms | 201ms | 134ms | 201.43
| PostPriorityStore.GetForPosts | p99 | 43ms | 129ms | 86ms | 198.73
| JobStore.GetNewestJobByStatusesAndType | p99 | 70ms | 208ms | 138ms | 198.56
| PostPersistentNotificationStore.GetSingle | p99 | 37ms | 110ms | 73ms | 198.54
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 14ms | 41ms | 27ms | 196.52
| ThreadStore.GetMembershipForUser | p99 | 35ms | 103ms | 68ms | 192.99
| ThreadStore.GetThreadsForUser | p99 | 42ms | 122ms | 80ms | 190.66
| PostAcknowledgementStore.GetForPosts | p99 | 40ms | 115ms | 75ms | 186.74
| TeamStore.GetTeamsForUser | p99 | 79ms | 216ms | 137ms | 174.39
| PostStore.GetPostsBefore | p99 | 46ms | 122ms | 76ms | 166.66
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 77ms | 205ms | 128ms | 166.49
| PreferenceStore.Get | p99 | 36ms | 95ms | 59ms | 161.94
| ChannelStore.GetFileCount | p99 | 49ms | 128ms | 79ms | 160.53
| ChannelStore.GetMemberLastViewedAt | p99 | 76ms | 197ms | 121ms | 160.15
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 75ms | 195ms | 120ms | 159.17
| ThreadStore.GetTotalUnreadThreads | p99 | 74ms | 192ms | 118ms | 158.96
| ChannelStore.SearchGroupChannels | p99 | 54ms | 139ms | 85ms | 158.39
| PostStore.GetPosts | p99 | 79ms | 204ms | 125ms | 157.73
| ChannelStore.GetChannels | p99 | 69ms | 178ms | 109ms | 157.11
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 37ms | 94ms | 57ms | 155.92
| ChannelStore.GetMembersForUser | p99 | 62ms | 157ms | 95ms | 154.29
| TeamStore.GetTeamsByUserId | p99 | 84ms | 212ms | 128ms | 151.86
| ChannelStore.GetGuestCount | p99 | 96ms | 240ms | 144ms | 150.69
| ThreadStore.GetThreadFollowers | p99 | 40ms | 100ms | 60ms | 150.23
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 81ms | 202ms | 121ms | 148.73
| ThreadStore.GetTeamsUnreadForUser | p99 | 84ms | 208ms | 124ms | 147.68
| TeamStore.GetAllPage | p99 | 87ms | 214ms | 127ms | 146.05
| ThreadStore.GetTotalThreads | p99 | 77ms | 190ms | 113ms | 146.03
| PreferenceStore.GetAll | p99 | 96ms | 235ms | 139ms | 144.31
| WebhookStore.GetOutgoingByTeam | p99 | 40ms | 96ms | 56ms | 141.20
| UserTermsOfServiceStore.GetByUser | p99 | 89ms | 215ms | 126ms | 141.13
| PostStore.GetPostReminders | p99 | 10ms | 24ms | 14ms | 140.70
| JobStore.UpdateStatus | p99 | 8ms | 19ms | 11ms | 140.50
| StatusStore.Get | p99 | 81ms | 194ms | 113ms | 139.79
| ThreadStore.GetTotalUnreadMentions | p99 | 77ms | 184ms | 107ms | 139.41
| SessionStore.GetLRUSessions | p99 | 93ms | 220ms | 127ms | 137.10
| UserStore.GetAllProfiles | p99 | 70ms | 164ms | 94ms | 134.88
| SessionStore.Save | p99 | 95ms | 223ms | 128ms | 134.13
| GroupStore.GetByName | p99 | 93ms | 217ms | 124ms | 133.74
| ChannelStore.GetByName | p99 | 88ms | 204ms | 116ms | 132.16
| PostStore.GetEtag | p99 | 89ms | 202ms | 113ms | 127.31
| UserStore.IsEmpty | p99 | 69ms | 154ms | 85ms | 124.00
| StatusStore.UpdateExpiredDNDStatuses | p99 | 10ms | 22ms | 12ms | 120.60
| JobStore.Get | p99 | 89ms | 195ms | 106ms | 119.10
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 229ms | 478ms | 249ms | 108.72
| SessionStore.Get | p99 | 106ms | 220ms | 114ms | 107.09
| UserStore.GetForLogin | p99 | 107ms | 220ms | 113ms | 105.33
| TokenStore.Cleanup | p99 | 5ms | 10ms | 5ms | 100.98
| CommandWebhookStore.Cleanup | p99 | 5ms | 10ms | 5ms | 100.98
| ChannelStore.CreateDirectChannel | p99 | 46ms | 91ms | 45ms | 98.36
| ChannelStore.SaveMember | p99 | 376ms | 730ms | 354ms | 94.17
| EmojiStore.GetByName | p99 | 42ms | 81ms | 39ms | 92.91
| ChannelStore.GetTeamChannels | p99 | 50ms | 96ms | 46ms | 92.43
| PostStore.SearchPostsForUser | p99 | 247ms | 463ms | 216ms | 87.52
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 91ms | 170ms | 79ms | 86.50
| PostStore.GetPostsAfter | p99 | 5ms | 9ms | 4ms | 80.81
| ThreadStore.MarkAllAsReadByChannels | p99 | 5ms | 9ms | 4ms | 80.81
| LinkMetadataStore.Save | p99 | 9ms | 16ms | 7ms | 77.21
| ChannelStore.GetMembersForUserWithPagination | p99 | 50ms | 85ms | 35ms | 70.35
| UserStore.AutocompleteUsersInChannel | p99 | 490ms | 828ms | 338ms | 69.02
| PostStore.GetPostsSince | p99 | 78ms | 128ms | 50ms | 64.28
| UserStore.Get | p99 | 5ms | 8ms | 3ms | 60.01
| ChannelStore.GetChannelsByUser | p99 | 153ms | 238ms | 85ms | 55.37
| JobStore.UpdateOptimistically | p99 | 10ms | 15ms | 5ms | 51.78
| ChannelStore.GetAllChannelMembersForUser | p99 | 49ms | 74ms | 25ms | 50.54
| UserStore.Count | p99 | 248ms | 370ms | 122ms | 49.17
| ChannelStore.CreateInitialSidebarCategories | p99 | 162ms | 239ms | 77ms | 47.43
| ChannelStore.GetMemberCount | p99 | 604ms | 877ms | 273ms | 45.24
| TeamStore.SaveMember | p99 | 246ms | 339ms | 93ms | 37.74
| UserStore.Search | p99 | 338ms | 428ms | 90ms | 26.63
| PostStore.Update | p99 | 28ms | 35ms | 7ms | 25.22
| ClusterDiscoveryStore.SetLastPingAt | p99 | 10ms | 12ms | 2ms | 20.57
| ChannelStore.GetMember | p99 | 19ms | 22ms | 3ms | 15.76
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.304s | 1.493s | 189ms | 14.49
| FileInfoStore.AttachToPost | p99 | 18ms | 20ms | 2ms | 11.14
| UserStore.GetAllProfilesInChannel | p99 | 2.12s | 2.286s | 166ms | 7.83
| UserStore.GetByUsername | p99 | 92ms | 95ms | 3ms | 3.26
| ChannelStore.UpdateSidebarCategories | p99 | 445ms | 453ms | 8ms | 1.80
| ProductNoticesStore.View | p99 | 169ms | 172ms | 3ms | 1.78
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPersistentNotificationStore.UpdateLastActivity | avg | 4ms | 0s | -4ms | -108.92
| PluginStore.List | avg | 5ms | 1ms | -4ms | -81.49
| UserStore.GetProfilesNotInChannel | avg | 14ms | 4ms | -10ms | -69.39
| PostStore.SearchPostsForUser | avg | 124ms | 57ms | -67ms | -53.90
| TeamStore.GetActiveMemberCount | avg | 223ms | 159ms | -64ms | -28.74
| ChannelStore.Save | avg | 20ms | 16ms | -4ms | -20.48
| TeamStore.GetTotalMemberCount | avg | 147ms | 128ms | -19ms | -12.90
| UserStore.Count | avg | 123ms | 110ms | -13ms | -10.59
| UserStore.AnalyticsActiveCount | avg | 216ms | 208ms | -8ms | -3.70
| ChannelStore.Autocomplete | avg | 1.519s | 1.484s | -35ms | -2.30
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.GetPostsByIds | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| TeamStore.GetMany | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetChannelsByIds | p99 | 5ms | 0s | -5ms | -101.01
| PluginStore.List | p99 | 190ms | 5ms | -185ms | -97.37
| UserStore.GetProfilesNotInChannel | p99 | 97ms | 5ms | -92ms | -94.85
| UserStore.GetProfilesInChannel | p99 | 33ms | 5ms | -28ms | -83.59
| TeamStore.GetActiveMemberCount | p99 | 970ms | 249ms | -721ms | -74.34
| PostStore.SetPostReminder | p99 | 24ms | 10ms | -14ms | -57.38
| ChannelStore.Save | p99 | 205ms | 88ms | -117ms | -57.07
| UserStore.Update | p99 | 21ms | 10ms | -11ms | -52.09
| TeamStore.GetTotalMemberCount | p99 | 485ms | 249ms | -236ms | -48.66
| RoleStore.ChannelHigherScopedPermissions | p99 | 8ms | 5ms | -3ms | -36.25
| PostPersistentNotificationStore.Get | p99 | 8ms | 5ms | -3ms | -35.71
| PostPriorityStore.GetForPost | p99 | 34ms | 22ms | -12ms | -34.91
| ChannelStore.IncrementMentionCount | p99 | 13ms | 11ms | -2ms | -15.43
| PostAcknowledgementStore.GetForPost | p99 | 23ms | 21ms | -2ms | -8.68
| UserStore.Save | p99 | 166ms | 158ms | -8ms | -4.81
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchFiles | avg | 6ms | 82ms | 76ms | 1289.27
| getTeamsForUser | avg | 4ms | 11ms | 7ms | 163.14
| getUser | avg | 5ms | 13ms | 8ms | 146.64
| getPreferences | avg | 6ms | 15ms | 9ms | 145.33
| getTeamMembersForUser | avg | 5ms | 12ms | 7ms | 134.85
| getCategoriesForTeamForUser | avg | 14ms | 32ms | 18ms | 129.21
| getAllTeams | avg | 5ms | 11ms | 6ms | 119.63
| getTeamsUnreadForUser | avg | 7ms | 15ms | 8ms | 118.40
| getChannelsForUser | avg | 15ms | 32ms | 17ms | 112.17
| getChannelsForTeamForUser | avg | 4ms | 8ms | 4ms | 105.32
| getThreadsForUser | avg | 3ms | 6ms | 3ms | 98.36
| getPostThread | avg | 6ms | 12ms | 6ms | 97.30
| getPostsForChannelAroundLastUnread | avg | 28ms | 55ms | 27ms | 96.07
| getUsersByNames | avg | 2ms | 4ms | 2ms | 94.37
| getChannelMember | avg | 9ms | 17ms | 8ms | 89.08
| saveReaction | avg | 7ms | 13ms | 6ms | 86.67
| getChannelMembersForTeamForUser | avg | 4ms | 7ms | 3ms | 84.27
| searchGroupChannels | avg | 3ms | 5ms | 2ms | 76.24
| unfollowThreadByUser | avg | 9ms | 16ms | 7ms | 74.24
| getPostsForChannel | avg | 19ms | 29ms | 10ms | 54.01
| getPublicChannelsForTeam | avg | 12ms | 17ms | 5ms | 42.21
| updateReadStateThreadByUser | avg | 21ms | 29ms | 8ms | 38.10
| getChannelStats | avg | 14ms | 19ms | 5ms | 36.76
| viewChannel | avg | 11ms | 15ms | 4ms | 35.80
| getUsers | avg | 7ms | 9ms | 2ms | 29.62
| autocompleteChannelsForTeamForSearch | avg | 143ms | 182ms | 39ms | 27.33
| login | avg | 71ms | 88ms | 17ms | 23.98
| addTeamMember | avg | 1.22s | 1.462s | 242ms | 19.83
| createPost | avg | 354ms | 409ms | 55ms | 15.52
| autocompleteUsers | avg | 149ms | 168ms | 19ms | 12.77
| getAnalytics | avg | 199ms | 221ms | 22ms | 11.08
| getLicenseSelfServeStatus | avg | 170ms | 188ms | 18ms | 10.60
| createUser | avg | 120ms | 132ms | 12ms | 9.96
| addChannelMember | avg | 186ms | 202ms | 16ms | 8.59
| searchUsers | avg | 89ms | 96ms | 7ms | 7.88
| createDirectChannel | avg | 176ms | 187ms | 11ms | 6.26
| updateCategoriesForTeamForUser | avg | 65ms | 68ms | 3ms | 4.59
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| unfollowThreadByUser | p99 | 23ms | 375ms | 352ms | 1504.77
| getChannel | p99 | 8ms | 72ms | 64ms | 842.12
| updateReadStateThreadByUser | p99 | 65ms | 525ms | 460ms | 705.90
| getPostThread | p99 | 60ms | 321ms | 261ms | 433.36
| searchPostsInTeam | p99 | 406ms | 1.667s | 1.261s | 310.72
| searchFiles | p99 | 25ms | 100ms | 75ms | 305.09
| getPublicChannelsForTeam | p99 | 51ms | 184ms | 133ms | 259.79
| getUsersByNames | p99 | 30ms | 91ms | 61ms | 200.31
| getThreadsForUser | p99 | 56ms | 160ms | 104ms | 184.75
| addChannelMember | p99 | 720ms | 1.95s | 1.23s | 170.83
| searchGroupChannels | p99 | 54ms | 139ms | 85ms | 158.39
| getTeamMembersForUser | p99 | 90ms | 228ms | 138ms | 152.84
| getTeamsForUser | p99 | 84ms | 212ms | 128ms | 151.83
| getChannelMembersForTeamForUser | p99 | 69ms | 169ms | 100ms | 144.48
| getPreferences | p99 | 97ms | 237ms | 140ms | 144.22
| getChannelsForTeamForUser | p99 | 84ms | 205ms | 121ms | 143.32
| viewChannel | p99 | 92ms | 221ms | 129ms | 140.85
| getUser | p99 | 95ms | 228ms | 133ms | 139.52
| getAllTeams | p99 | 94ms | 221ms | 127ms | 135.78
| getPostsForChannelAroundLastUnread | p99 | 374ms | 855ms | 481ms | 128.56
| getUsers | p99 | 70ms | 155ms | 85ms | 122.26
| getPostsForChannel | p99 | 221ms | 489ms | 268ms | 121.46
| saveReaction | p99 | 162ms | 339ms | 177ms | 109.15
| getCategoriesForTeamForUser | p99 | 231ms | 479ms | 248ms | 107.22
| upsertDraft | p99 | 5ms | 10ms | 5ms | 101.01
| getTeamsUnreadForUser | p99 | 138ms | 268ms | 130ms | 93.99
| getClientConfig | p99 | 48ms | 92ms | 44ms | 91.03
| getTeamMember | p99 | 5ms | 9ms | 4ms | 78.24
| login | p99 | 430ms | 757ms | 327ms | 76.02
| getChannelMember | p99 | 147ms | 243ms | 96ms | 65.36
| autocompleteUsers | p99 | 473ms | 725ms | 252ms | 53.26
| getFilePreview | p99 | 99ms | 141ms | 42ms | 42.45
| getChannelStats | p99 | 336ms | 456ms | 120ms | 35.69
| searchUsers | p99 | 342ms | 430ms | 88ms | 25.76
| autocompleteChannelsForTeamForSearch | p99 | 1.304s | 1.493s | 189ms | 14.49
| getChannelsForUser | p99 | 221ms | 249ms | 28ms | 12.67
| createUser | p99 | 437ms | 486ms | 49ms | 11.21
| createPost | p99 | 2.224s | 2.41s | 186ms | 8.36
| addTeamMember | p99 | 4.638s | 4.887s | 249ms | 5.37
| getFileThumbnail | p99 | 94ms | 99ms | 5ms | 5.34
| updateCategoriesForTeamForUser | p99 | 448ms | 453ms | 5ms | 1.12
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getFilteredUsersStats | avg | 69ms | 28ms | -41ms | -59.12
| searchPostsInTeam | avg | 132ms | 73ms | -59ms | -44.61
| handleCheckCWSConnection | avg | 53ms | 32ms | -21ms | -39.61
| getTeamStats | avg | 224ms | 161ms | -63ms | -28.09
| patchPost | avg | 32ms | 25ms | -7ms | -21.90
| logout | avg | 40ms | 37ms | -3ms | -7.52
| createChannel | avg | 241ms | 223ms | -18ms | -7.48
| getProfileImage | avg | 94ms | 88ms | -6ms | -6.40
| createGroupChannel | avg | 302ms | 283ms | -19ms | -6.29
| removeUserCustomStatus | avg | 124ms | 120ms | -4ms | -3.21
| uploadFileStream | avg | 393ms | 381ms | -12ms | -3.05
| searchAllChannels | avg | 1.519s | 1.484s | -35ms | -2.30
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getSchemes | p99 | 5ms | 0s | -5ms | -101.01
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| getFilteredUsersStats | p99 | 247ms | 50ms | -197ms | -79.76
| patchPost | p99 | 389ms | 96ms | -293ms | -75.37
| getTeamStats | p99 | 970ms | 249ms | -721ms | -74.34
| handleCheckCWSConnection | p99 | 100ms | 50ms | -50ms | -50.25
| createGroupChannel | p99 | 1.72s | 1.57s | -150ms | -8.72
| createDirectChannel | p99 | 480ms | 469ms | -11ms | -2.29
| createChannel | p99 | 493ms | 482ms | -11ms | -2.23
| getProfileImage | p99 | 457ms | 452ms | -5ms | -1.09
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| BotStore.Get |  Avg| 1ms| 6ms | 5ms | 485.149
| |  P99| 5ms| 90ms | 85ms | 1717.172
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 274ms| 272ms | -2ms | -0.729
| |  P99| 497ms| 497ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 5ms | 1ms | 22.381
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.AnalyticsTypeCount |  Avg| 3ms| 5ms | 2ms | 60.968
| |  P99| 5ms| 24ms | 19ms | 383.838
| ChannelStore.Autocomplete |  Avg| 1.519s| 1.484s | -35ms | -2.305
| |  P99| 4.944s| 4.952s | 8ms | 0.162
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 143ms| 182ms | 39ms | 27.336
| |  P99| 1.304s| 1.493s | 189ms | 14.494
| ChannelStore.CreateDirectChannel |  Avg| 19ms| 21ms | 2ms | 10.569
| |  P99| 46ms| 91ms | 45ms | 98.361
| ChannelStore.CreateInitialSidebarCategories |  Avg| 25ms| 32ms | 7ms | 27.623
| |  P99| 162ms| 239ms | 77ms | 47.430
| ChannelStore.Get |  Avg| 3ms| 8ms | 5ms | 182.729
| |  P99| 67ms| 201ms | 134ms | 201.433
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 11ms| 16ms | 5ms | 46.439
| |  P99| 44ms| 197ms | 153ms | 349.715
| ChannelStore.GetAllChannelMembersForUser |  Avg| 8ms| 9ms | 1ms | 12.493
| |  P99| 49ms| 74ms | 25ms | 50.544
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 16ms | 3ms | 23.036
| |  P99| 91ms| 170ms | 79ms | 86.500
| ChannelStore.GetByName |  Avg| 5ms| 11ms | 6ms | 109.282
| |  P99| 88ms| 204ms | 116ms | 132.161
| ChannelStore.GetByNameIncludeDeleted |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 3ms| 6ms | 3ms | 99.454
| |  P99| 69ms| 178ms | 109ms | 157.112
| ChannelStore.GetChannelsByIds |  Avg| 1ms| 0s | -1ms | -155.845
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelsByUser |  Avg| 13ms| 27ms | 14ms | 105.596
| |  P99| 153ms| 238ms | 85ms | 55.375
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 3ms | 1ms | 55.360
| |  P99| 37ms| 94ms | 57ms | 155.915
| ChannelStore.GetFileCount |  Avg| 4ms| 6ms | 2ms | 51.703
| |  P99| 49ms| 128ms | 79ms | 160.530
| ChannelStore.GetGuestCount |  Avg| 6ms| 15ms | 9ms | 159.935
| |  P99| 96ms| 240ms | 144ms | 150.685
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 22ms | 3ms | 15.756
| ChannelStore.GetMemberCount |  Avg| 133ms| 186ms | 53ms | 39.867
| |  P99| 604ms| 877ms | 273ms | 45.235
| ChannelStore.GetMemberForPost |  Avg| 2ms| 3ms | 1ms | 59.184
| |  P99| 28ms| 94ms | 66ms | 238.671
| ChannelStore.GetMemberLastViewedAt |  Avg| 4ms| 9ms | 5ms | 139.184
| |  P99| 76ms| 197ms | 121ms | 160.148
| ChannelStore.GetMembers |  Avg| 1ms| 0s | -1ms | -108.434
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 3ms| 6ms | 3ms | 94.216
| |  P99| 62ms| 157ms | 95ms | 154.295
| ChannelStore.GetMembersForUserWithPagination |  Avg| 40ms| 44ms | 4ms | 9.911
| |  P99| 50ms| 85ms | 35ms | 70.352
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 2ms | 1ms | 87.877
| |  P99| 22ms| 23ms | 1ms | 4.494
| ChannelStore.GetPublicChannelsForTeam |  Avg| 11ms| 16ms | 5ms | 47.094
| |  P99| 51ms| 184ms | 133ms | 259.794
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 14ms| 32ms | 18ms | 131.808
| |  P99| 229ms| 478ms | 249ms | 108.720
| ChannelStore.GetSidebarCategory |  Avg| 5ms| 6ms | 1ms | 20.403
| |  P99| 10ms| 41ms | 31ms | 312.197
| ChannelStore.GetTeamChannels |  Avg| 32ms| 35ms | 3ms | 9.395
| |  P99| 50ms| 96ms | 46ms | 92.435
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 11ms | -2ms | -15.434
| ChannelStore.Save |  Avg| 20ms| 16ms | -4ms | -20.479
| |  P99| 205ms| 88ms | -117ms | -57.073
| ChannelStore.SaveMember |  Avg| 41ms| 63ms | 22ms | 54.229
| |  P99| 376ms| 730ms | 354ms | 94.170
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 5ms | 2ms | 78.067
| |  P99| 54ms| 139ms | 85ms | 158.385
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.300
| ChannelStore.UpdateSidebarCategories |  Avg| 51ms| 54ms | 3ms | 5.872
| |  P99| 445ms| 453ms | 8ms | 1.798
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.570
| CommandWebhookStore.Cleanup |  Avg| 2ms| 6ms | 4ms | 192.782
| |  P99| 5ms| 10ms | 5ms | 100.981
| ComplianceStore.MessageExport |  Avg| 1ms| 2ms | 1ms | 70.464
| |  P99| 5ms| 21ms | 16ms | 323.232
| DraftStore.Delete |  Avg| 2ms| 3ms | 1ms | 47.834
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 3ms | 1ms | 59.363
| |  P99| 42ms| 81ms | 39ms | 92.912
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.138
| FileInfoStore.Get |  Avg| 1ms| 2ms | 1ms | 98.500
| |  P99| 6ms| 46ms | 40ms | 615.469
| FileInfoStore.GetForPost |  Avg| 1ms| 3ms | 2ms | 189.410
| |  P99| 5ms| 58ms | 53ms | 1063.588
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.Search |  Avg| 5ms| 82ms | 77ms | 1663.147
| |  P99| 25ms| 100ms | 75ms | 305.092
| FileInfoStore.SetContent |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.132
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 4ms| 9ms | 5ms | 135.360
| |  P99| 77ms| 205ms | 128ms | 166.492
| GroupStore.GetByName |  Avg| 5ms| 11ms | 6ms | 123.009
| |  P99| 93ms| 217ms | 124ms | 133.743
| GroupStore.GetGroups |  Avg| 3ms| 5ms | 2ms | 71.767
| |  P99| 49ms| 154ms | 105ms | 216.089
| JobStore.Get |  Avg| 2ms| 5ms | 3ms | 132.854
| |  P99| 89ms| 195ms | 106ms | 119.101
| JobStore.GetAllByStatus |  Avg| 2ms| 4ms | 2ms | 110.703
| |  P99| 25ms| 94ms | 69ms | 278.788
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 7ms | 6ms | 472.622
| |  P99| 31ms| 200ms | 169ms | 549.593
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 8ms | 5ms | 175.778
| |  P99| 70ms| 208ms | 138ms | 198.561
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 15ms | 5ms | 51.782
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 19ms | 11ms | 140.499
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| LicenseStore.GetAll |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 3ms | 2ms | 190.625
| |  P99| 11ms| 75ms | 64ms | 589.431
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 16ms | 7ms | 77.206
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 5ms| 1ms | -4ms | -81.488
| |  P99| 190ms| 5ms | -185ms | -97.368
| PluginStore.SetWithOptions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.677
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 5ms | 3ms | 125.352
| |  P99| 40ms| 115ms | 75ms | 186.744
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.714
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 4ms | 2ms | 112.262
| |  P99| 37ms| 110ms | 73ms | 198.540
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 4ms| 0s | -4ms | -108.925
| |  P99| 5ms| 0s | -5ms | -101.010
| PostPriorityStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -63.695
| |  P99| 34ms| 22ms | -12ms | -34.911
| PostPriorityStore.GetForPosts |  Avg| 2ms| 5ms | 3ms | 125.680
| |  P99| 43ms| 129ms | 86ms | 198.729
| PostStore.Delete |  Avg| 15ms| 14ms | -1ms | -6.830
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 6ms | 2ms | 47.321
| |  P99| 47ms| 147ms | 100ms | 213.196
| PostStore.GetEtag |  Avg| 4ms| 8ms | 4ms | 101.159
| |  P99| 89ms| 202ms | 113ms | 127.311
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.359
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 24ms | 14ms | 140.704
| PostStore.GetPosts |  Avg| 7ms| 12ms | 5ms | 76.105
| |  P99| 79ms| 204ms | 125ms | 157.731
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostStore.GetPostsBefore |  Avg| 3ms| 5ms | 2ms | 58.645
| |  P99| 46ms| 122ms | 76ms | 166.662
| PostStore.GetPostsByIds |  Avg| 1ms| 0s | -1ms | -124.630
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.GetPostsByThread |  Avg| 1ms| 2ms | 1ms | 86.680
| |  P99| 5ms| 47ms | 42ms | 840.342
| PostStore.GetPostsSince |  Avg| 9ms| 10ms | 1ms | 11.696
| |  P99| 78ms| 128ms | 50ms | 64.283
| PostStore.GetSingle |  Avg| 1ms| 3ms | 2ms | 165.012
| |  P99| 9ms| 74ms | 65ms | 736.140
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 124ms| 57ms | -67ms | -53.899
| |  P99| 247ms| 463ms | 216ms | 87.521
| PostStore.SetPostReminder |  Avg| 9ms| 8ms | -1ms | -11.708
| |  P99| 24ms| 10ms | -14ms | -57.375
| PostStore.Update |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 28ms| 35ms | 7ms | 25.224
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 4ms | 2ms | 110.027
| |  P99| 36ms| 95ms | 59ms | 161.937
| PreferenceStore.GetAll |  Avg| 6ms| 15ms | 9ms | 150.917
| |  P99| 96ms| 235ms | 139ms | 144.306
| PreferenceStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 47ms| 48ms | 1ms | 2.125
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 42ms| 42ms | 0s | 0.000
| |  P99| 169ms| 172ms | 3ms | 1.777
| ReactionStore.GetForPost |  Avg| 3ms| 4ms | 1ms | 36.202
| |  P99| 24ms| 91ms | 67ms | 276.631
| RetentionPolicyStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -36.254
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 8ms| 14ms | 6ms | 72.298
| |  P99| 106ms| 220ms | 114ms | 107.094
| SessionStore.GetLRUSessions |  Avg| 5ms| 11ms | 6ms | 130.796
| |  P99| 93ms| 220ms | 127ms | 137.104
| SessionStore.GetSessionsExpired |  Avg| 8ms| 36ms | 28ms | 364.902
| |  P99| 48ms| 242ms | 194ms | 400.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 2ms | 1ms | 96.758
| |  P99| 14ms| 41ms | 27ms | 196.516
| SessionStore.Remove |  Avg| 5ms| 4ms | -1ms | -21.840
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Save |  Avg| 10ms| 16ms | 6ms | 62.537
| |  P99| 95ms| 223ms | 128ms | 134.133
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.Get |  Avg| 4ms| 8ms | 4ms | 109.239
| |  P99| 81ms| 194ms | 113ms | 139.786
| StatusStore.GetByIds |  Avg| 1ms| 3ms | 2ms | 169.721
| |  P99| 18ms| 135ms | 117ms | 637.606
| StatusStore.SaveOrUpdate |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 7ms| 8ms | 1ms | 13.345
| |  P99| 10ms| 22ms | 12ms | 120.603
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.528
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -5.740
| SystemStore.PermanentDeleteByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SystemStore.SaveOrUpdate |  Avg| 3ms| 4ms | 1ms | 29.119
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 3ms | 2ms | 152.818
| |  P99| 22ms| 92ms | 70ms | 311.722
| TeamStore.GetActiveMemberCount |  Avg| 223ms| 159ms | -64ms | -28.737
| |  P99| 970ms| 249ms | -721ms | -74.336
| TeamStore.GetAllPage |  Avg| 4ms| 10ms | 6ms | 140.180
| |  P99| 87ms| 214ms | 127ms | 146.054
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 4ms| 9ms | 5ms | 123.518
| |  P99| 81ms| 202ms | 121ms | 148.730
| TeamStore.GetMany |  Avg| 1ms| 0s | -1ms | -160.030
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 4ms| 11ms | 7ms | 165.693
| |  P99| 84ms| 212ms | 128ms | 151.858
| TeamStore.GetTeamsForUser |  Avg| 4ms| 10ms | 6ms | 149.250
| |  P99| 79ms| 216ms | 137ms | 174.390
| TeamStore.GetTotalMemberCount |  Avg| 147ms| 128ms | -19ms | -12.897
| |  P99| 485ms| 249ms | -236ms | -48.660
| TeamStore.SaveMember |  Avg| 100ms| 107ms | 7ms | 7.020
| |  P99| 246ms| 339ms | 93ms | 37.735
| ThreadStore.Get |  Avg| 1ms| 4ms | 3ms | 520.588
| |  P99| 5ms| 163ms | 158ms | 3191.919
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 4ms | 2ms | 118.253
| |  P99| 35ms| 103ms | 68ms | 192.990
| ThreadStore.GetTeamsUnreadForUser |  Avg| 5ms| 10ms | 5ms | 105.197
| |  P99| 84ms| 208ms | 124ms | 147.683
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 4ms | 2ms | 107.893
| |  P99| 40ms| 100ms | 60ms | 150.235
| ThreadStore.GetThreadForUser |  Avg| 3ms| 5ms | 2ms | 63.924
| |  P99| 39ms| 136ms | 97ms | 245.943
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 2ms | 1ms | 77.956
| |  P99| 8ms| 53ms | 45ms | 576.193
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 5ms | 3ms | 123.377
| |  P99| 42ms| 122ms | 80ms | 190.656
| ThreadStore.GetTotalThreads |  Avg| 4ms| 8ms | 4ms | 108.760
| |  P99| 77ms| 190ms | 113ms | 146.027
| ThreadStore.GetTotalUnreadMentions |  Avg| 4ms| 7ms | 3ms | 84.857
| |  P99| 77ms| 184ms | 107ms | 139.414
| ThreadStore.GetTotalUnreadThreads |  Avg| 4ms| 8ms | 4ms | 109.082
| |  P99| 74ms| 192ms | 118ms | 158.961
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 4ms| 8ms | 4ms | 106.241
| |  P99| 75ms| 195ms | 120ms | 159.173
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.581
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 6ms | 4ms | 194.510
| |  P99| 5ms| 10ms | 5ms | 100.981
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 216ms| 208ms | -8ms | -3.701
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 191ms| 210ms | 19ms | 9.967
| |  P99| 490ms| 828ms | 338ms | 69.019
| UserStore.Count |  Avg| 123ms| 110ms | -13ms | -10.588
| |  P99| 248ms| 370ms | 122ms | 49.169
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.005
| UserStore.GetAllProfiles |  Avg| 6ms| 9ms | 3ms | 52.917
| |  P99| 70ms| 164ms | 94ms | 134.880
| UserStore.GetAllProfilesInChannel |  Avg| 438ms| 502ms | 64ms | 14.611
| |  P99| 2.12s| 2.286s | 166ms | 7.829
| UserStore.GetByUsername |  Avg| 3ms| 5ms | 2ms | 73.392
| |  P99| 92ms| 95ms | 3ms | 3.261
| UserStore.GetForLogin |  Avg| 5ms| 12ms | 7ms | 129.657
| |  P99| 107ms| 220ms | 113ms | 105.330
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.739
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 4ms | 2ms | 101.118
| |  P99| 30ms| 91ms | 61ms | 202.829
| UserStore.GetProfilesInChannel |  Avg| 2ms| 1ms | -1ms | -40.424
| |  P99| 33ms| 5ms | -28ms | -83.585
| UserStore.GetProfilesNotInChannel |  Avg| 14ms| 4ms | -10ms | -69.388
| |  P99| 97ms| 5ms | -92ms | -94.846
| UserStore.GetUnreadCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 43ms| 141ms | 98ms | 229.585
| UserStore.IsEmpty |  Avg| 3ms| 7ms | 4ms | 128.882
| |  P99| 69ms| 154ms | 85ms | 124.003
| UserStore.Save |  Avg| 69ms| 70ms | 1ms | 1.448
| |  P99| 166ms| 158ms | -8ms | -4.806
| UserStore.Search |  Avg| 87ms| 95ms | 8ms | 9.162
| |  P99| 338ms| 428ms | 90ms | 26.627
| UserStore.Update |  Avg| 7ms| 6ms | -1ms | -15.058
| |  P99| 21ms| 10ms | -11ms | -52.094
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.983
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 4ms| 11ms | 7ms | 162.196
| |  P99| 89ms| 215ms | 126ms | 141.127
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 5ms | 2ms | 57.560
| |  P99| 40ms| 96ms | 56ms | 141.198
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 186ms| 202ms | 16ms | 8.591
| | P99| 720ms| 1.95s | 1.23s | 170.830
| addTeamMember | Avg| 1.22s| 1.462s | 242ms | 19.829
| | P99| 4.638s| 4.887s | 249ms | 5.368
| autocompleteChannelsForTeamForSearch | Avg| 143ms| 182ms | 39ms | 27.325
| | P99| 1.304s| 1.493s | 189ms | 14.494
| autocompleteUsers | Avg| 149ms| 168ms | 19ms | 12.771
| | P99| 473ms| 725ms | 252ms | 53.259
| createChannel | Avg| 241ms| 223ms | -18ms | -7.484
| | P99| 493ms| 482ms | -11ms | -2.231
| createDirectChannel | Avg| 176ms| 187ms | 11ms | 6.258
| | P99| 480ms| 469ms | -11ms | -2.292
| createGroupChannel | Avg| 302ms| 283ms | -19ms | -6.285
| | P99| 1.72s| 1.57s | -150ms | -8.721
| createPost | Avg| 354ms| 409ms | 55ms | 15.516
| | P99| 2.224s| 2.41s | 186ms | 8.364
| createUser | Avg| 120ms| 132ms | 12ms | 9.963
| | P99| 437ms| 486ms | 49ms | 11.208
| deleteDraft | Avg| 1ms| 2ms | 1ms | 127.321
| | P99| 5ms| 5ms | 0s | 0.000
| deletePost | Avg| 17ms| 18ms | 1ms | 6.005
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 9ms| 10ms | 1ms | 10.831
| | P99| 24ms| 24ms | 0s | 0.000
| getAllTeams | Avg| 5ms| 11ms | 6ms | 119.632
| | P99| 94ms| 221ms | 127ms | 135.775
| getAnalytics | Avg| 199ms| 221ms | 22ms | 11.077
| | P99| 490ms| 494ms | 4ms | 0.816
| getCategoriesForTeamForUser | Avg| 14ms| 32ms | 18ms | 129.207
| | P99| 231ms| 479ms | 248ms | 107.218
| getChannel | Avg| 2ms| 3ms | 1ms | 45.532
| | P99| 8ms| 72ms | 64ms | 842.125
| getChannelMember | Avg| 9ms| 17ms | 8ms | 89.079
| | P99| 147ms| 243ms | 96ms | 65.359
| getChannelMembers | Avg| 1ms| 0s | -1ms | -101.259
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 4ms| 7ms | 3ms | 84.270
| | P99| 69ms| 169ms | 100ms | 144.482
| getChannelStats | Avg| 14ms| 19ms | 5ms | 36.757
| | P99| 336ms| 456ms | 120ms | 35.689
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 4ms| 8ms | 4ms | 105.321
| | P99| 84ms| 205ms | 121ms | 143.320
| getChannelsForUser | Avg| 15ms| 32ms | 17ms | 112.168
| | P99| 221ms| 249ms | 28ms | 12.670
| getClientConfig | Avg| 8ms| 9ms | 1ms | 12.555
| | P99| 48ms| 92ms | 44ms | 91.028
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 36ms| 37ms | 1ms | 2.768
| | P99| 99ms| 141ms | 42ms | 42.450
| getFileThumbnail | Avg| 29ms| 30ms | 1ms | 3.466
| | P99| 94ms| 99ms | 5ms | 5.343
| getFilteredUsersStats | Avg| 69ms| 28ms | -41ms | -59.124
| | P99| 247ms| 50ms | -197ms | -79.757
| getGroups | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getLicenseSelfServeStatus | Avg| 170ms| 188ms | 18ms | 10.604
| | P99| 249ms| 249ms | 0s | 0.000
| getPostThread | Avg| 6ms| 12ms | 6ms | 97.303
| | P99| 60ms| 321ms | 261ms | 433.359
| getPostsForChannel | Avg| 19ms| 29ms | 10ms | 54.013
| | P99| 221ms| 489ms | 268ms | 121.456
| getPostsForChannelAroundLastUnread | Avg| 28ms| 55ms | 27ms | 96.073
| | P99| 374ms| 855ms | 481ms | 128.556
| getPreferences | Avg| 6ms| 15ms | 9ms | 145.334
| | P99| 97ms| 237ms | 140ms | 144.224
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 94ms| 88ms | -6ms | -6.403
| | P99| 457ms| 452ms | -5ms | -1.093
| getPublicChannelsForTeam | Avg| 12ms| 17ms | 5ms | 42.209
| | P99| 51ms| 184ms | 133ms | 259.794
| getRolesByNames | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getSchemes | Avg| 1ms| 0s | -1ms | -148.404
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 9ms | 4ms | 78.241
| getTeamMembersForUser | Avg| 5ms| 12ms | 7ms | 134.854
| | P99| 90ms| 228ms | 138ms | 152.841
| getTeamStats | Avg| 224ms| 161ms | -63ms | -28.095
| | P99| 970ms| 249ms | -721ms | -74.336
| getTeamsForUser | Avg| 4ms| 11ms | 7ms | 163.135
| | P99| 84ms| 212ms | 128ms | 151.828
| getTeamsUnreadForUser | Avg| 7ms| 15ms | 8ms | 118.402
| | P99| 138ms| 268ms | 130ms | 93.990
| getThreadsForUser | Avg| 3ms| 6ms | 3ms | 98.360
| | P99| 56ms| 160ms | 104ms | 184.750
| getUser | Avg| 5ms| 13ms | 8ms | 146.638
| | P99| 95ms| 228ms | 133ms | 139.521
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 7ms| 9ms | 2ms | 29.623
| | P99| 70ms| 155ms | 85ms | 122.261
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 4ms | 2ms | 94.372
| | P99| 30ms| 91ms | 61ms | 200.308
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 53ms| 32ms | -21ms | -39.606
| | P99| 100ms| 50ms | -50ms | -50.251
| login | Avg| 71ms| 88ms | 17ms | 23.976
| | P99| 430ms| 757ms | 327ms | 76.022
| logout | Avg| 40ms| 37ms | -3ms | -7.520
| | P99| 96ms| 95ms | -1ms | -1.042
| patchPost | Avg| 32ms| 25ms | -7ms | -21.902
| | P99| 389ms| 96ms | -293ms | -75.368
| removeUserCustomStatus | Avg| 124ms| 120ms | -4ms | -3.213
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 7ms| 13ms | 6ms | 86.672
| | P99| 162ms| 339ms | 177ms | 109.154
| searchAllChannels | Avg| 1.519s| 1.484s | -35ms | -2.304
| | P99| 4.944s| 4.952s | 8ms | 0.162
| searchFiles | Avg| 6ms| 82ms | 76ms | 1289.270
| | P99| 25ms| 100ms | 75ms | 305.092
| searchGroupChannels | Avg| 3ms| 5ms | 2ms | 76.244
| | P99| 54ms| 139ms | 85ms | 158.385
| searchPostsInTeam | Avg| 132ms| 73ms | -59ms | -44.609
| | P99| 406ms| 1.667s | 1.261s | 310.723
| searchUsers | Avg| 89ms| 96ms | 7ms | 7.878
| | P99| 342ms| 430ms | 88ms | 25.758
| setPostReminder | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| unfollowThreadByUser | Avg| 9ms| 16ms | 7ms | 74.242
| | P99| 23ms| 375ms | 352ms | 1504.775
| updateCategoriesForTeamForUser | Avg| 65ms| 68ms | 3ms | 4.593
| | P99| 448ms| 453ms | 5ms | 1.117
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 21ms| 29ms | 8ms | 38.098
| | P99| 65ms| 525ms | 460ms | 705.896
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 393ms| 381ms | -12ms | -3.052
| | P99| 992ms| 984ms | -8ms | -0.807
| upsertDraft | Avg| 3ms| 4ms | 1ms | 33.967
| | P99| 5ms| 10ms | 5ms | 101.010
| viewChannel | Avg| 11ms| 15ms | 4ms | 35.805
| | P99| 92ms| 221ms | 129ms | 140.850
