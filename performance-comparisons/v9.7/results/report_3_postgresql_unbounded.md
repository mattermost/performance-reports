### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMembersForUser | avg | 1ms | 12ms | 11ms | 1200.07
| TokenStore.Cleanup | avg | 1ms | 17ms | 16ms | 1097.29
| CommandWebhookStore.Cleanup | avg | 2ms | 19ms | 17ms | 803.11
| StatusStore.UpdateExpiredDNDStatuses | avg | 2ms | 12ms | 10ms | 452.85
| LicenseStore.GetAll | avg | 1ms | 3ms | 2ms | 373.39
| PostStore.GetPostReminders | avg | 5ms | 13ms | 8ms | 151.89
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 8ms | 20ms | 12ms | 148.65
| PreferenceStore.DeleteCategoryAndName | avg | 8ms | 19ms | 11ms | 137.30
| PostStore.Delete | avg | 30ms | 64ms | 34ms | 112.10
| UserStore.GetByUsername | avg | 7ms | 13ms | 6ms | 84.93
| PluginStore.List | avg | 7ms | 12ms | 5ms | 76.39
| EmojiStore.GetMultipleByName | avg | 7ms | 11ms | 4ms | 55.97
| BotStore.Get | avg | 4ms | 6ms | 2ms | 55.31
| PostStore.SetPostReminder | avg | 16ms | 24ms | 8ms | 48.78
| PostStore.Update | avg | 23ms | 32ms | 9ms | 39.47
| JobStore.Save | avg | 6ms | 8ms | 2ms | 35.74
| PostStore.GetPostIdBeforeTime | avg | 6ms | 8ms | 2ms | 31.24
| ThreadStore.MarkAllAsReadByChannels | avg | 7ms | 9ms | 2ms | 28.12
| PostPriorityStore.GetForPost | avg | 7ms | 9ms | 2ms | 27.03
| PreferenceStore.Save | avg | 16ms | 20ms | 4ms | 24.29
| ChannelStore.CreateDirectChannel | avg | 54ms | 64ms | 10ms | 18.60
| ProductNoticesStore.View | avg | 55ms | 65ms | 10ms | 18.08
| ChannelStore.GetMemberForPost | avg | 13ms | 15ms | 2ms | 15.79
| FileInfoStore.AttachToPost | avg | 14ms | 16ms | 2ms | 14.50
| ThreadStore.MaintainMembership | avg | 15ms | 17ms | 2ms | 13.55
| FileInfoStore.SetContent | avg | 17ms | 19ms | 2ms | 12.09
| PostStore.Save | avg | 26ms | 29ms | 3ms | 11.76
| StatusStore.SaveOrUpdate | avg | 75ms | 82ms | 7ms | 9.30
| ChannelStore.Save | avg | 36ms | 39ms | 3ms | 8.38
| ChannelStore.CreateInitialSidebarCategories | avg | 53ms | 56ms | 3ms | 5.63
| UserStore.Save | avg | 81ms | 84ms | 3ms | 3.69
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TokenStore.Cleanup | p99 | 5ms | 49ms | 44ms | 888.67
| CommandWebhookStore.Cleanup | p99 | 5ms | 49ms | 44ms | 888.56
| LicenseStore.GetAll | p99 | 5ms | 24ms | 19ms | 383.84
| PostStore.GetPostReminders | p99 | 44ms | 211ms | 167ms | 379.55
| StatusStore.UpdateExpiredDNDStatuses | p99 | 21ms | 94ms | 73ms | 341.12
| ChannelStore.GetAllChannelMembersForUser | p99 | 23ms | 93ms | 70ms | 306.93
| BotStore.Get | p99 | 21ms | 86ms | 65ms | 303.74
| UserStore.GetByUsername | p99 | 79ms | 220ms | 141ms | 178.48
| PostStore.SetPostReminder | p99 | 88ms | 230ms | 142ms | 162.28
| PostStore.GetPostReminderMetadata | p99 | 87ms | 212ms | 125ms | 142.86
| PostPriorityStore.GetForPost | p99 | 72ms | 147ms | 75ms | 103.57
| PreferenceStore.DeleteCategoryAndName | p99 | 47ms | 95ms | 48ms | 102.67
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 47ms | 95ms | 48ms | 102.67
| EmojiStore.GetMultipleByName | p99 | 24ms | 48ms | 24ms | 98.06
| PostStore.Delete | p99 | 231ms | 455ms | 224ms | 97.18
| UserStore.GetMany | p99 | 24ms | 45ms | 21ms | 86.60
| ProductNoticesStore.View | p99 | 494ms | 763ms | 269ms | 54.49
| JobStore.GetAllByStatus | p99 | 100ms | 152ms | 52ms | 51.83
| JobStore.UpdateStatusOptimistically | p99 | 45ms | 66ms | 21ms | 47.19
| TeamStore.GetMember | p99 | 26ms | 38ms | 12ms | 45.78
| SessionStore.Save | p99 | 97ms | 140ms | 43ms | 44.24
| ChannelStore.GetChannelsByUser | p99 | 90ms | 123ms | 33ms | 36.70
| PostStore.Update | p99 | 221ms | 299ms | 78ms | 35.37
| ChannelStore.GetChannelUnread | p99 | 89ms | 119ms | 30ms | 33.86
| ChannelStore.GetMemberForPost | p99 | 94ms | 123ms | 29ms | 30.92
| WebhookStore.GetOutgoingByTeam | p99 | 108ms | 139ms | 31ms | 28.62
| PostStore.Save | p99 | 249ms | 317ms | 68ms | 27.36
| UserStore.Save | p99 | 276ms | 344ms | 68ms | 24.67
| StatusStore.Get | p99 | 59ms | 73ms | 14ms | 23.80
| PostStore.GetPostIdAfterTime | p99 | 52ms | 63ms | 11ms | 21.04
| PluginStore.List | p99 | 167ms | 202ms | 35ms | 20.90
| PostAcknowledgementStore.GetForPost | p99 | 77ms | 93ms | 16ms | 20.86
| ThreadStore.GetThreadsForUser | p99 | 99ms | 119ms | 20ms | 20.19
| UserStore.IsEmpty | p99 | 35ms | 42ms | 7ms | 19.97
| SystemStore.GetByName | p99 | 66ms | 78ms | 12ms | 18.12
| ChannelStore.SearchGroupChannels | p99 | 118ms | 139ms | 21ms | 17.75
| AuditStore.Save | p99 | 69ms | 81ms | 12ms | 17.40
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 54ms | 63ms | 9ms | 16.78
| PostStore.GetPostsBefore | p99 | 99ms | 115ms | 16ms | 16.24
| ChannelStore.CreateDirectChannel | p99 | 429ms | 497ms | 68ms | 15.85
| PluginStore.Delete | p99 | 46ms | 53ms | 7ms | 15.27
| UserStore.UpdateLastLogin | p99 | 57ms | 65ms | 8ms | 13.92
| UserStore.GetForLogin | p99 | 74ms | 84ms | 10ms | 13.48
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 82ms | 93ms | 11ms | 13.40
| ThreadStore.GetTeamsUnreadForUser | p99 | 111ms | 125ms | 14ms | 12.56
| StatusStore.GetByIds | p99 | 98ms | 110ms | 12ms | 12.29
| SessionStore.Get | p99 | 168ms | 186ms | 18ms | 10.72
| FileInfoStore.SetContent | p99 | 189ms | 209ms | 20ms | 10.60
| GroupStore.GetByName | p99 | 72ms | 79ms | 7ms | 9.70
| UserTermsOfServiceStore.GetByUser | p99 | 73ms | 80ms | 7ms | 9.56
| PostStore.GetEtag | p99 | 98ms | 107ms | 9ms | 9.17
| ThreadStore.GetThreadFollowers | p99 | 80ms | 87ms | 7ms | 8.73
| PreferenceStore.Save | p99 | 214ms | 232ms | 18ms | 8.42
| ChannelStore.UpdateLastViewedAt | p99 | 84ms | 91ms | 7ms | 8.33
| UserStore.Get | p99 | 75ms | 81ms | 6ms | 7.97
| StatusStore.UpdateLastActivityAt | p99 | 81ms | 87ms | 6ms | 7.37
| PostStore.GetPostIdBeforeTime | p99 | 85ms | 91ms | 6ms | 7.04
| EmojiStore.GetByName | p99 | 86ms | 92ms | 6ms | 6.98
| ThreadStore.MarkAllAsReadByChannels | p99 | 88ms | 94ms | 6ms | 6.80
| PluginStore.SetWithOptions | p99 | 93ms | 99ms | 6ms | 6.43
| TeamStore.GetAllPage | p99 | 80ms | 85ms | 5ms | 6.26
| SessionStore.UpdateLastActivityAt | p99 | 82ms | 87ms | 5ms | 6.12
| TeamStore.GetTeamsForUser | p99 | 82ms | 87ms | 5ms | 6.09
| ChannelStore.IncrementMentionCount | p99 | 82ms | 87ms | 5ms | 6.06
| GroupStore.GetGroups | p99 | 88ms | 93ms | 5ms | 5.70
| ChannelStore.GetFileCount | p99 | 89ms | 94ms | 5ms | 5.59
| PostStore.GetPosts | p99 | 72ms | 76ms | 4ms | 5.57
| PostPersistentNotificationStore.Get | p99 | 75ms | 79ms | 4ms | 5.37
| ThreadStore.MaintainMembership | p99 | 205ms | 216ms | 11ms | 5.37
| ChannelStore.CreateInitialSidebarCategories | p99 | 418ms | 439ms | 21ms | 5.02
| UserStore.UpdateUpdateAt | p99 | 60ms | 63ms | 3ms | 4.99
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 84ms | 88ms | 4ms | 4.76
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 85ms | 89ms | 4ms | 4.73
| UserStore.GetUnreadCount | p99 | 88ms | 92ms | 4ms | 4.56
| PreferenceStore.GetAll | p99 | 88ms | 92ms | 4ms | 4.54
| PostAcknowledgementStore.GetForPosts | p99 | 156ms | 163ms | 7ms | 4.48
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 91ms | 95ms | 4ms | 4.40
| UserStore.GetProfilesByUsernames | p99 | 96ms | 100ms | 4ms | 4.18
| FileInfoStore.AttachToPost | p99 | 173ms | 180ms | 7ms | 4.04
| ThreadStore.MarkAsRead | p99 | 80ms | 83ms | 3ms | 3.76
| FileInfoStore.Get | p99 | 95ms | 98ms | 3ms | 3.16
| PreferenceStore.Get | p99 | 95ms | 98ms | 3ms | 3.14
| UserStore.UpdateFailedPasswordAttempts | p99 | 76ms | 78ms | 2ms | 2.62
| PostPriorityStore.GetForPosts | p99 | 162ms | 166ms | 4ms | 2.48
| ThreadStore.UpdateMembership | p99 | 82ms | 84ms | 2ms | 2.45
| ThreadStore.GetTotalUnreadThreads | p99 | 85ms | 87ms | 2ms | 2.36
| TeamStore.Get | p99 | 86ms | 88ms | 2ms | 2.34
| ChannelStore.GetByName | p99 | 86ms | 88ms | 2ms | 2.33
| PostStore.Get | p99 | 217ms | 222ms | 5ms | 2.31
| PostStore.GetSingle | p99 | 88ms | 90ms | 2ms | 2.26
| ThreadStore.GetMembershipForUser | p99 | 91ms | 93ms | 2ms | 2.19
| ChannelStore.GetMember | p99 | 92ms | 94ms | 2ms | 2.18
| ChannelStore.GetPinnedPostCount | p99 | 93ms | 95ms | 2ms | 2.16
| ChannelStore.GetMembersForUser | p99 | 96ms | 98ms | 2ms | 2.07
| ChannelStore.GetChannels | p99 | 97ms | 99ms | 2ms | 2.07
| UserStore.GetProfileByIds | p99 | 97ms | 99ms | 2ms | 2.07
| StatusStore.SaveOrUpdate | p99 | 932ms | 948ms | 16ms | 1.72
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SessionStore.GetLRUSessions | avg | 6ms | 0s | -6ms | -109.03
| BotStore.Save | avg | 2ms | 0s | -2ms | -107.36
| PostPersistentNotificationStore.UpdateLastActivity | avg | 5ms | 0s | -5ms | -103.62
| TeamStore.GetMany | avg | 12ms | 0s | -12ms | -102.90
| SystemStore.Save | avg | 2ms | 0s | -2ms | -101.44
| ChannelStore.GetForPost | avg | 44ms | 0s | -44ms | -100.22
| PostStore.GetPostsByIds | avg | 5ms | 0s | -5ms | -99.46
| ChannelStore.GetChannelsByIds | avg | 9ms | 0s | -9ms | -99.37
| TeamStore.GetByName | avg | 6ms | 0s | -6ms | -93.15
| ChannelStore.GetMembers | avg | 42ms | 3ms | -39ms | -92.89
| DraftStore.Upsert | avg | 2ms | 0s | -2ms | -83.70
| PluginStore.Get | avg | 22ms | 5ms | -17ms | -77.77
| UserStore.GetProfilesInChannel | avg | 373ms | 93ms | -280ms | -75.12
| ThreadStore.MarkAllAsReadByTeam | avg | 3ms | 1ms | -2ms | -72.78
| SessionStore.GetSessionsExpired | avg | 7ms | 3ms | -4ms | -58.55
| ProductNoticesStore.ClearOldNotices | avg | 77ms | 36ms | -41ms | -53.25
| RoleStore.ChannelHigherScopedPermissions | avg | 15ms | 8ms | -7ms | -46.25
| ChannelStore.GetTeamChannels | avg | 84ms | 47ms | -37ms | -43.97
| ChannelStore.CreateSidebarCategory | avg | 63ms | 36ms | -27ms | -42.96
| JobStore.Get | avg | 8ms | 5ms | -3ms | -36.35
| UserStore.Count | avg | 33ms | 21ms | -12ms | -36.23
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 43ms | 28ms | -15ms | -34.77
| ChannelStore.AutocompleteInTeamForSearch | avg | 127ms | 88ms | -39ms | -30.66
| JobStore.UpdateStatus | avg | 7ms | 5ms | -2ms | -29.94
| PostStore.AnalyticsPostCount | avg | 653ms | 460ms | -193ms | -29.55
| ChannelStore.GetMembersForUserWithPagination | avg | 21ms | 15ms | -6ms | -28.82
| LinkMetadataStore.Save | avg | 11ms | 8ms | -3ms | -28.07
| ChannelStore.UpdateSidebarCategories | avg | 124ms | 92ms | -32ms | -25.74
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 34ms | 27ms | -7ms | -20.64
| SessionStore.Remove | avg | 11ms | 9ms | -2ms | -18.81
| UserStore.AutocompleteUsersInChannel | avg | 91ms | 75ms | -16ms | -17.61
| StatusStore.GetByIds | avg | 12ms | 10ms | -2ms | -16.79
| ChannelStore.GetSidebarCategory | avg | 26ms | 22ms | -4ms | -15.18
| PostStore.SearchPostsForUser | avg | 289ms | 247ms | -42ms | -14.53
| UserStore.Search | avg | 62ms | 54ms | -8ms | -12.93
| ChannelStore.Autocomplete | avg | 67ms | 59ms | -8ms | -11.95
| ThreadStore.GetThreadUnreadReplyCount | avg | 17ms | 15ms | -2ms | -11.88
| ChannelStore.GetPublicChannelsForTeam | avg | 35ms | 31ms | -4ms | -11.42
| PostStore.GetPostsSince | avg | 28ms | 25ms | -3ms | -10.73
| ChannelStore.GetMemberCount | avg | 38ms | 34ms | -4ms | -10.66
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 43ms | 40ms | -3ms | -6.90
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.GetPostsByIds | p99 | 24ms | 0s | -24ms | -101.88
| SystemStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.InvalidateChannelByName | p99 | 5ms | 0s | -5ms | -100.98
| ChannelStore.InvalidateAllChannelMembersForUser | p99 | 5ms | 0s | -5ms | -100.98
| DraftStore.Upsert | p99 | 5ms | 0s | -5ms | -100.93
| ChannelStore.GetForPost | p99 | 99ms | 0s | -99ms | -100.00
| TeamStore.GetMany | p99 | 94ms | 0s | -94ms | -100.00
| ChannelStore.GetChannelsByIds | p99 | 47ms | 0s | -47ms | -100.00
| TeamStore.GetByName | p99 | 77ms | 0s | -77ms | -99.89
| SessionStore.GetLRUSessions | p99 | 62ms | 0s | -62ms | -99.68
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 24ms | 0s | -24ms | -98.85
| ChannelStore.GetMembers | p99 | 99ms | 5ms | -94ms | -94.95
| SessionStore.Remove | p99 | 215ms | 48ms | -167ms | -77.50
| ChannelStore.CreateSidebarCategory | p99 | 245ms | 97ms | -148ms | -60.29
| RoleStore.ChannelHigherScopedPermissions | p99 | 130ms | 54ms | -76ms | -58.46
| UserStore.Count | p99 | 220ms | 93ms | -127ms | -57.73
| ChannelStore.UpdateSidebarCategories | p99 | 1.84s | 785ms | -1.055s | -57.34
| UserStore.GetProfilesInChannel | p99 | 980ms | 435ms | -545ms | -55.61
| PluginStore.Get | p99 | 97ms | 45ms | -52ms | -53.33
| SessionStore.GetSessionsExpired | p99 | 48ms | 24ms | -24ms | -50.26
| ProductNoticesStore.ClearOldNotices | p99 | 100ms | 50ms | -50ms | -50.25
| PostStore.AnalyticsPostCount | p99 | 995ms | 498ms | -497ms | -49.95
| ChannelStore.GetTeamChannels | p99 | 475ms | 241ms | -234ms | -49.26
| ChannelStore.Save | p99 | 457ms | 246ms | -211ms | -46.20
| ChannelStore.AutocompleteInTeamForSearch | p99 | 4.046s | 2.205s | -1.841s | -45.50
| PostPersistentNotificationStore.DeleteExpired | p99 | 81ms | 47ms | -34ms | -42.23
| JobStore.GetCountByStatusAndType | p99 | 148ms | 99ms | -49ms | -33.11
| PostStore.SearchPostsForUser | p99 | 3.424s | 2.409s | -1.015s | -29.65
| LinkMetadataStore.Save | p99 | 93ms | 69ms | -24ms | -25.70
| ThreadStore.GetThreadUnreadReplyCount | p99 | 130ms | 97ms | -33ms | -25.43
| JobStore.UpdateStatus | p99 | 84ms | 66ms | -18ms | -21.56
| UserStore.AutocompleteUsersInChannel | p99 | 459ms | 361ms | -98ms | -21.35
| ThreadStore.Get | p99 | 116ms | 94ms | -22ms | -19.01
| ChannelStore.Autocomplete | p99 | 283ms | 239ms | -44ms | -15.52
| JobStore.GetNewestJobByStatusesAndType | p99 | 66ms | 56ms | -10ms | -15.15
| UserStore.Update | p99 | 244ms | 209ms | -35ms | -14.34
| ChannelStore.GetMemberCount | p99 | 228ms | 197ms | -31ms | -13.62
| ChannelStore.GetSidebarCategory | p99 | 217ms | 192ms | -25ms | -11.52
| UserStore.GetAllProfiles | p99 | 56ms | 50ms | -6ms | -10.64
| ChannelStore.GetPublicChannelsForTeam | p99 | 237ms | 212ms | -25ms | -10.54
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 243ms | 219ms | -24ms | -9.86
| ReactionStore.GetForPost | p99 | 95ms | 86ms | -9ms | -9.50
| PostStore.GetPostsSince | p99 | 220ms | 204ms | -16ms | -7.29
| ChannelStore.Get | p99 | 116ms | 108ms | -8ms | -6.90
| PostStore.GetPostsAfter | p99 | 87ms | 81ms | -6ms | -6.89
| UserStore.Search | p99 | 249ms | 234ms | -15ms | -6.03
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 245ms | 234ms | -11ms | -4.48
| ChannelStore.GetMembersForUserWithPagination | p99 | 95ms | 92ms | -3ms | -3.14
| JobStore.Save | p99 | 67ms | 65ms | -2ms | -2.99
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 237ms | 231ms | -6ms | -2.53
| ChannelStore.GetGuestCount | p99 | 93ms | 91ms | -2ms | -2.15
| ChannelStore.SaveMember | p99 | 455ms | 446ms | -9ms | -1.98
| UserStore.GetAllProfilesInChannel | p99 | 2.302s | 2.26s | -42ms | -1.82
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| upsertDraft | avg | 3ms | 29ms | 26ms | 866.75
| patchPost | avg | 140ms | 599ms | 459ms | 327.89
| getPrevTrialLicense | avg | 1ms | 4ms | 3ms | 284.21
| deletePost | avg | 51ms | 117ms | 66ms | 128.59
| createUser | avg | 131ms | 240ms | 109ms | 83.17
| updatePreferences | avg | 28ms | 36ms | 8ms | 28.84
| getClientConfig | avg | 14ms | 16ms | 2ms | 14.43
| unfollowThreadByUser | avg | 48ms | 54ms | 6ms | 12.60
| viewChannel | avg | 34ms | 38ms | 4ms | 11.75
| removeUserCustomStatus | avg | 316ms | 351ms | 35ms | 11.08
| createDirectChannel | avg | 435ms | 476ms | 41ms | 9.43
| getProfileImage | avg | 80ms | 86ms | 6ms | 7.49
| login | avg | 153ms | 164ms | 11ms | 7.20
| uploadFileStream | avg | 458ms | 484ms | 26ms | 5.68
| createPost | avg | 808ms | 827ms | 19ms | 2.35
| addTeamMember | avg | 1.289s | 1.303s | 14ms | 1.09
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| upsertDraft | p99 | 5ms | 243ms | 238ms | 4804.27
| getPrevTrialLicense | p99 | 5ms | 24ms | 19ms | 383.84
| deletePost | p99 | 240ms | 910ms | 670ms | 278.87
| createUser | p99 | 645ms | 1.709s | 1.064s | 164.90
| removeUserCustomStatus | p99 | 973ms | 2.02s | 1.047s | 107.55
| setPostReminder | p99 | 244ms | 433ms | 189ms | 77.54
| getChannelUnread | p99 | 95ms | 152ms | 57ms | 59.80
| updatePreferences | p99 | 250ms | 372ms | 122ms | 48.82
| getTeamMember | p99 | 94ms | 131ms | 37ms | 39.16
| getChannelsForUser | p99 | 92ms | 127ms | 35ms | 38.01
| login | p99 | 987ms | 1.34s | 353ms | 35.75
| getChannelsForTeamForUser | p99 | 100ms | 123ms | 23ms | 23.09
| getThreadsForUser | p99 | 118ms | 143ms | 25ms | 21.25
| getUsersByNames | p99 | 97ms | 117ms | 20ms | 20.56
| searchGroupChannels | p99 | 118ms | 142ms | 24ms | 20.29
| getUserStatusesByIds | p99 | 21ms | 25ms | 4ms | 19.17
| createGroupChannel | p99 | 3.733s | 4.375s | 642ms | 17.20
| getChannel | p99 | 165ms | 192ms | 27ms | 16.35
| getTeamMembersForUser | p99 | 96ms | 110ms | 14ms | 14.59
| unfollowThreadByUser | p99 | 381ms | 427ms | 46ms | 12.08
| getUsersByIds | p99 | 34ms | 38ms | 4ms | 11.93
| viewChannel | p99 | 363ms | 401ms | 38ms | 10.46
| uploadFileStream | p99 | 1.945s | 2.143s | 198ms | 10.18
| getTeamsUnreadForUser | p99 | 178ms | 193ms | 15ms | 8.42
| getClientConfig | p99 | 209ms | 226ms | 17ms | 8.14
| getChannelMembersForTeamForUser | p99 | 99ms | 105ms | 6ms | 6.09
| createDirectChannel | p99 | 2.232s | 2.361s | 129ms | 5.78
| getUser | p99 | 204ms | 215ms | 11ms | 5.39
| getAllTeams | p99 | 94ms | 99ms | 5ms | 5.32
| getPreferences | p99 | 92ms | 95ms | 3ms | 3.27
| getProfileImage | p99 | 464ms | 478ms | 14ms | 3.02
| getPostsForChannelAroundLastUnread | p99 | 439ms | 452ms | 13ms | 2.96
| saveReaction | p99 | 243ms | 248ms | 5ms | 2.06
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 43ms | 4ms | -39ms | -91.31
| updateReadStateAllThreadsByUser | avg | 3ms | 1ms | -2ms | -69.82
| createChannel | avg | 84ms | 47ms | -37ms | -43.89
| getChannelStats | avg | 10ms | 6ms | -4ms | -41.23
| createCategoryForTeamForUser | avg | 71ms | 43ms | -28ms | -39.41
| autocompleteChannelsForTeamForSearch | avg | 127ms | 88ms | -39ms | -30.65
| updateCategoriesForTeamForUser | avg | 186ms | 132ms | -54ms | -29.04
| getFileThumbnail | avg | 58ms | 47ms | -11ms | -19.08
| autocompleteUsers | avg | 78ms | 65ms | -13ms | -16.59
| getPublicChannelsForTeam | avg | 37ms | 32ms | -5ms | -13.60
| followThreadByUser | avg | 59ms | 51ms | -8ms | -13.53
| searchAllChannels | avg | 68ms | 59ms | -9ms | -13.33
| searchPostsInTeam | avg | 314ms | 273ms | -41ms | -13.07
| searchUsers | avg | 64ms | 56ms | -8ms | -12.43
| getFilePreview | avg | 65ms | 57ms | -8ms | -12.23
| setPostReminder | avg | 60ms | 54ms | -6ms | -10.06
| getCategoriesForTeamForUser | avg | 44ms | 40ms | -4ms | -9.13
| logout | avg | 163ms | 152ms | -11ms | -6.76
| getPostThread | avg | 52ms | 49ms | -3ms | -5.74
| getPostsForChannel | avg | 97ms | 92ms | -5ms | -5.17
| updateReadStateThreadByUser | avg | 123ms | 119ms | -4ms | -3.25
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 99ms | 5ms | -94ms | -94.95
| createCategoryForTeamForUser | p99 | 245ms | 99ms | -146ms | -59.47
| updateCategoriesForTeamForUser | p99 | 1.84s | 898ms | -942ms | -51.20
| createChannel | p99 | 475ms | 241ms | -234ms | -49.26
| followThreadByUser | p99 | 830ms | 433ms | -397ms | -47.83
| logout | p99 | 885ms | 480ms | -405ms | -45.76
| getChannelStats | p99 | 178ms | 97ms | -81ms | -45.61
| autocompleteChannelsForTeamForSearch | p99 | 4.046s | 2.205s | -1.841s | -45.50
| searchPostsInTeam | p99 | 3.724s | 2.439s | -1.285s | -34.51
| autocompleteUsers | p99 | 438ms | 316ms | -122ms | -27.88
| patchPost | p99 | 3.038s | 2.2s | -838ms | -27.59
| getFileThumbnail | p99 | 314ms | 248ms | -66ms | -21.05
| addChannelMember | p99 | 2.8s | 2.292s | -508ms | -18.14
| getFilePreview | p99 | 361ms | 302ms | -59ms | -16.36
| searchAllChannels | p99 | 283ms | 240ms | -43ms | -15.17
| getPublicChannelsForTeam | p99 | 237ms | 212ms | -25ms | -10.54
| searchUsers | p99 | 250ms | 237ms | -13ms | -5.20
| createPost | p99 | 4.564s | 4.483s | -81ms | -1.77
| addTeamMember | p99 | 6.849s | 6.754s | -95ms | -1.39
| getCategoriesForTeamForUser | p99 | 237ms | 234ms | -3ms | -1.26
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 6ms| 7ms | 1ms | 16.515
| |  P99| 69ms| 81ms | 12ms | 17.401
| BotStore.Get |  Avg| 4ms| 6ms | 2ms | 55.308
| |  P99| 21ms| 86ms | 65ms | 303.738
| BotStore.Save |  Avg| 2ms| 0s | -2ms | -107.364
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 54ms| 63ms | 9ms | 16.779
| ChannelStore.Autocomplete |  Avg| 67ms| 59ms | -8ms | -11.947
| |  P99| 283ms| 239ms | -44ms | -15.525
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 127ms| 88ms | -39ms | -30.662
| |  P99| 4.046s| 2.205s | -1.841s | -45.504
| ChannelStore.CreateDirectChannel |  Avg| 54ms| 64ms | 10ms | 18.599
| |  P99| 429ms| 497ms | 68ms | 15.847
| ChannelStore.CreateInitialSidebarCategories |  Avg| 53ms| 56ms | 3ms | 5.634
| |  P99| 418ms| 439ms | 21ms | 5.023
| ChannelStore.CreateSidebarCategory |  Avg| 63ms| 36ms | -27ms | -42.963
| |  P99| 245ms| 97ms | -148ms | -60.285
| ChannelStore.Get |  Avg| 12ms| 11ms | -1ms | -8.618
| |  P99| 116ms| 108ms | -8ms | -6.895
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 34ms| 27ms | -7ms | -20.638
| |  P99| 243ms| 219ms | -24ms | -9.864
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 12ms | 11ms | 1200.073
| |  P99| 23ms| 93ms | 70ms | 306.927
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 43ms| 28ms | -15ms | -34.773
| |  P99| 245ms| 234ms | -11ms | -4.484
| ChannelStore.GetByName |  Avg| 8ms| 9ms | 1ms | 12.140
| |  P99| 86ms| 88ms | 2ms | 2.332
| ChannelStore.GetChannelUnread |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 89ms| 119ms | 30ms | 33.861
| ChannelStore.GetChannels |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 97ms| 99ms | 2ms | 2.070
| ChannelStore.GetChannelsByIds |  Avg| 9ms| 0s | -9ms | -99.368
| |  P99| 47ms| 0s | -47ms | -99.999
| ChannelStore.GetChannelsByUser |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 90ms| 123ms | 33ms | 36.704
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 91ms| 95ms | 4ms | 4.400
| ChannelStore.GetFileCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 89ms| 94ms | 5ms | 5.591
| ChannelStore.GetForPost |  Avg| 44ms| 0s | -44ms | -100.215
| |  P99| 99ms| 0s | -99ms | -100.000
| ChannelStore.GetGuestCount |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 93ms| 91ms | -2ms | -2.154
| ChannelStore.GetMember |  Avg| 8ms| 9ms | 1ms | 12.999
| |  P99| 92ms| 94ms | 2ms | 2.182
| ChannelStore.GetMemberCount |  Avg| 38ms| 34ms | -4ms | -10.656
| |  P99| 228ms| 197ms | -31ms | -13.623
| ChannelStore.GetMemberForPost |  Avg| 13ms| 15ms | 2ms | 15.791
| |  P99| 94ms| 123ms | 29ms | 30.917
| ChannelStore.GetMemberLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 77ms| 78ms | 1ms | 1.301
| ChannelStore.GetMembers |  Avg| 42ms| 3ms | -39ms | -92.895
| |  P99| 99ms| 5ms | -94ms | -94.949
| ChannelStore.GetMembersForUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 96ms| 98ms | 2ms | 2.073
| ChannelStore.GetMembersForUserWithPagination |  Avg| 21ms| 15ms | -6ms | -28.818
| |  P99| 95ms| 92ms | -3ms | -3.141
| ChannelStore.GetPinnedPostCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 93ms| 95ms | 2ms | 2.160
| ChannelStore.GetPublicChannelsForTeam |  Avg| 35ms| 31ms | -4ms | -11.419
| |  P99| 237ms| 212ms | -25ms | -10.536
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 43ms| 40ms | -3ms | -6.903
| |  P99| 237ms| 231ms | -6ms | -2.534
| ChannelStore.GetSidebarCategory |  Avg| 26ms| 22ms | -4ms | -15.178
| |  P99| 217ms| 192ms | -25ms | -11.521
| ChannelStore.GetTeamChannels |  Avg| 84ms| 47ms | -37ms | -43.970
| |  P99| 475ms| 241ms | -234ms | -49.263
| ChannelStore.IncrementMentionCount |  Avg| 6ms| 7ms | 1ms | 16.192
| |  P99| 82ms| 87ms | 5ms | 6.062
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -100.977
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -100.984
| ChannelStore.Save |  Avg| 36ms| 39ms | 3ms | 8.376
| |  P99| 457ms| 246ms | -211ms | -46.204
| ChannelStore.SaveMember |  Avg| 54ms| 54ms | 0s | 0.000
| |  P99| 455ms| 446ms | -9ms | -1.980
| ChannelStore.SearchGroupChannels |  Avg| 19ms| 18ms | -1ms | -5.264
| |  P99| 118ms| 139ms | 21ms | 17.751
| ChannelStore.UpdateLastViewedAt |  Avg| 8ms| 9ms | 1ms | 12.295
| |  P99| 84ms| 91ms | 7ms | 8.335
| ChannelStore.UpdateSidebarCategories |  Avg| 124ms| 92ms | -32ms | -25.736
| |  P99| 1.84s| 785ms | -1.055s | -57.339
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 6ms| 7ms | 1ms | 17.419
| |  P99| 82ms| 93ms | 11ms | 13.404
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 97ms| 96ms | -1ms | -1.027
| CommandWebhookStore.Cleanup |  Avg| 2ms| 19ms | 17ms | 803.105
| |  P99| 5ms| 49ms | 44ms | 888.558
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 8ms| 20ms | 12ms | 148.648
| |  P99| 47ms| 95ms | 48ms | 102.673
| DraftStore.Upsert |  Avg| 2ms| 0s | -2ms | -83.702
| |  P99| 5ms| 0s | -5ms | -100.930
| EmojiStore.GetByName |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 86ms| 92ms | 6ms | 6.982
| EmojiStore.GetMultipleByName |  Avg| 7ms| 11ms | 4ms | 55.973
| |  P99| 24ms| 48ms | 24ms | 98.060
| FileInfoStore.AttachToPost |  Avg| 14ms| 16ms | 2ms | 14.503
| |  P99| 173ms| 180ms | 7ms | 4.041
| FileInfoStore.Get |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 95ms| 98ms | 3ms | 3.158
| FileInfoStore.GetForPost |  Avg| 9ms| 8ms | -1ms | -10.935
| |  P99| 92ms| 92ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 11ms| 12ms | 1ms | 9.182
| |  P99| 97ms| 98ms | 1ms | 1.027
| FileInfoStore.SetContent |  Avg| 17ms| 19ms | 2ms | 12.087
| |  P99| 189ms| 209ms | 20ms | 10.603
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 72ms| 72ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 5ms| 6ms | 1ms | 18.704
| |  P99| 72ms| 79ms | 7ms | 9.702
| GroupStore.GetGroups |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 88ms| 93ms | 5ms | 5.698
| JobStore.Get |  Avg| 8ms| 5ms | -3ms | -36.350
| |  P99| 67ms| 66ms | -1ms | -1.492
| JobStore.GetAllByStatus |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 100ms| 152ms | 52ms | 51.827
| JobStore.GetCountByStatusAndType |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 148ms| 99ms | -49ms | -33.108
| JobStore.GetNewestJobByStatusesAndType |  Avg| 7ms| 6ms | -1ms | -15.072
| |  P99| 66ms| 56ms | -10ms | -15.152
| JobStore.Save |  Avg| 6ms| 8ms | 2ms | 35.745
| |  P99| 67ms| 65ms | -2ms | -2.985
| JobStore.UpdateOptimistically |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 67ms| 66ms | -1ms | -1.492
| JobStore.UpdateStatus |  Avg| 7ms| 5ms | -2ms | -29.938
| |  P99| 84ms| 66ms | -18ms | -21.556
| JobStore.UpdateStatusOptimistically |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 45ms| 66ms | 21ms | 47.191
| LicenseStore.GetAll |  Avg| 1ms| 3ms | 2ms | 373.390
| |  P99| 5ms| 24ms | 19ms | 383.838
| LinkMetadataStore.Get |  Avg| 9ms| 8ms | -1ms | -11.718
| |  P99| 90ms| 91ms | 1ms | 1.109
| LinkMetadataStore.Save |  Avg| 11ms| 8ms | -3ms | -28.069
| |  P99| 93ms| 69ms | -24ms | -25.703
| PluginStore.Delete |  Avg| 3ms| 4ms | 1ms | 29.016
| |  P99| 46ms| 53ms | 7ms | 15.275
| PluginStore.Get |  Avg| 22ms| 5ms | -17ms | -77.773
| |  P99| 97ms| 45ms | -52ms | -53.334
| PluginStore.List |  Avg| 7ms| 12ms | 5ms | 76.392
| |  P99| 167ms| 202ms | 35ms | 20.896
| PluginStore.SetWithOptions |  Avg| 8ms| 9ms | 1ms | 12.452
| |  P99| 93ms| 99ms | 6ms | 6.429
| PostAcknowledgementStore.GetForPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 77ms| 93ms | 16ms | 20.860
| PostAcknowledgementStore.GetForPosts |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 156ms| 163ms | 7ms | 4.482
| PostPersistentNotificationStore.DeleteExpired |  Avg| 5ms| 4ms | -1ms | -19.176
| |  P99| 81ms| 47ms | -34ms | -42.231
| PostPersistentNotificationStore.Get |  Avg| 4ms| 5ms | 1ms | 26.460
| |  P99| 75ms| 79ms | 4ms | 5.368
| PostPersistentNotificationStore.GetSingle |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 80ms| 79ms | -1ms | -1.254
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 5ms| 0s | -5ms | -103.623
| |  P99| 24ms| 0s | -24ms | -98.851
| PostPriorityStore.GetForPost |  Avg| 7ms| 9ms | 2ms | 27.034
| |  P99| 72ms| 147ms | 75ms | 103.571
| PostPriorityStore.GetForPosts |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 162ms| 166ms | 4ms | 2.475
| PostStore.AnalyticsPostCount |  Avg| 653ms| 460ms | -193ms | -29.553
| |  P99| 995ms| 498ms | -497ms | -49.950
| PostStore.Delete |  Avg| 30ms| 64ms | 34ms | 112.100
| |  P99| 231ms| 455ms | 224ms | 97.179
| PostStore.Get |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 217ms| 222ms | 5ms | 2.309
| PostStore.GetEtag |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 98ms| 107ms | 9ms | 9.168
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 5ms | 1ms | 23.702
| |  P99| 52ms| 63ms | 11ms | 21.043
| PostStore.GetPostIdBeforeTime |  Avg| 6ms| 8ms | 2ms | 31.243
| |  P99| 85ms| 91ms | 6ms | 7.039
| PostStore.GetPostReminderMetadata |  Avg| 10ms| 11ms | 1ms | 10.245
| |  P99| 87ms| 212ms | 125ms | 142.858
| PostStore.GetPostReminders |  Avg| 5ms| 13ms | 8ms | 151.891
| |  P99| 44ms| 211ms | 167ms | 379.545
| PostStore.GetPosts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 72ms| 76ms | 4ms | 5.571
| PostStore.GetPostsAfter |  Avg| 10ms| 9ms | -1ms | -9.733
| |  P99| 87ms| 81ms | -6ms | -6.894
| PostStore.GetPostsBefore |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 99ms| 115ms | 16ms | 16.235
| PostStore.GetPostsByIds |  Avg| 5ms| 0s | -5ms | -99.463
| |  P99| 24ms| 0s | -24ms | -101.877
| PostStore.GetPostsByThread |  Avg| 14ms| 13ms | -1ms | -6.920
| |  P99| 96ms| 95ms | -1ms | -1.040
| PostStore.GetPostsSince |  Avg| 28ms| 25ms | -3ms | -10.733
| |  P99| 220ms| 204ms | -16ms | -7.287
| PostStore.GetSingle |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 90ms | 2ms | 2.262
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 26ms| 29ms | 3ms | 11.760
| |  P99| 249ms| 317ms | 68ms | 27.356
| PostStore.SearchPostsForUser |  Avg| 289ms| 247ms | -42ms | -14.532
| |  P99| 3.424s| 2.409s | -1.015s | -29.648
| PostStore.SetPostReminder |  Avg| 16ms| 24ms | 8ms | 48.778
| |  P99| 88ms| 230ms | 142ms | 162.284
| PostStore.Update |  Avg| 23ms| 32ms | 9ms | 39.471
| |  P99| 221ms| 299ms | 78ms | 35.374
| PreferenceStore.DeleteCategoryAndName |  Avg| 8ms| 19ms | 11ms | 137.303
| |  P99| 47ms| 95ms | 48ms | 102.673
| PreferenceStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 95ms| 98ms | 3ms | 3.144
| PreferenceStore.GetAll |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 92ms | 4ms | 4.542
| PreferenceStore.Save |  Avg| 16ms| 20ms | 4ms | 24.292
| |  P99| 214ms| 232ms | 18ms | 8.416
| ProductNoticesStore.ClearOldNotices |  Avg| 77ms| 36ms | -41ms | -53.249
| |  P99| 100ms| 50ms | -50ms | -50.248
| ProductNoticesStore.View |  Avg| 55ms| 65ms | 10ms | 18.081
| |  P99| 494ms| 763ms | 269ms | 54.490
| ReactionStore.GetForPost |  Avg| 10ms| 9ms | -1ms | -9.756
| |  P99| 95ms| 86ms | -9ms | -9.504
| RoleStore.ChannelHigherScopedPermissions |  Avg| 15ms| 8ms | -7ms | -46.252
| |  P99| 130ms| 54ms | -76ms | -58.462
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 12ms| 13ms | 1ms | 8.132
| |  P99| 168ms| 186ms | 18ms | 10.721
| SessionStore.GetLRUSessions |  Avg| 6ms| 0s | -6ms | -109.029
| |  P99| 62ms| 0s | -62ms | -99.685
| SessionStore.GetSessionsExpired |  Avg| 7ms| 3ms | -4ms | -58.546
| |  P99| 48ms| 24ms | -24ms | -50.261
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 8ms| 7ms | -1ms | -12.557
| |  P99| 85ms| 86ms | 1ms | 1.173
| SessionStore.Remove |  Avg| 11ms| 9ms | -2ms | -18.810
| |  P99| 215ms| 48ms | -167ms | -77.498
| SessionStore.Save |  Avg| 11ms| 12ms | 1ms | 9.082
| |  P99| 97ms| 140ms | 43ms | 44.235
| SessionStore.UpdateLastActivityAt |  Avg| 8ms| 9ms | 1ms | 12.975
| |  P99| 82ms| 87ms | 5ms | 6.115
| StatusStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 59ms| 73ms | 14ms | 23.803
| StatusStore.GetByIds |  Avg| 12ms| 10ms | -2ms | -16.789
| |  P99| 98ms| 110ms | 12ms | 12.294
| StatusStore.SaveOrUpdate |  Avg| 75ms| 82ms | 7ms | 9.302
| |  P99| 932ms| 948ms | 16ms | 1.716
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 12ms | 10ms | 452.854
| |  P99| 21ms| 94ms | 73ms | 341.121
| StatusStore.UpdateLastActivityAt |  Avg| 7ms| 8ms | 1ms | 13.957
| |  P99| 81ms| 87ms | 6ms | 7.375
| SystemStore.GetByName |  Avg| 4ms| 5ms | 1ms | 23.653
| |  P99| 66ms| 78ms | 12ms | 18.123
| SystemStore.Save |  Avg| 2ms| 0s | -2ms | -101.438
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.Get |  Avg| 8ms| 7ms | -1ms | -13.227
| |  P99| 86ms| 88ms | 2ms | 2.339
| TeamStore.GetAllPage |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 80ms| 85ms | 5ms | 6.259
| TeamStore.GetByName |  Avg| 6ms| 0s | -6ms | -93.149
| |  P99| 77ms| 0s | -77ms | -99.891
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 8ms| 7ms | -1ms | -13.294
| |  P99| 84ms| 88ms | 4ms | 4.762
| TeamStore.GetMany |  Avg| 12ms| 0s | -12ms | -102.897
| |  P99| 94ms| 0s | -94ms | -99.999
| TeamStore.GetMember |  Avg| 2ms| 3ms | 1ms | 46.117
| |  P99| 26ms| 38ms | 12ms | 45.779
| TeamStore.GetTeamsByUserId |  Avg| 7ms| 6ms | -1ms | -15.206
| |  P99| 83ms| 82ms | -1ms | -1.210
| TeamStore.GetTeamsForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 82ms| 87ms | 5ms | 6.087
| TeamStore.SaveMember |  Avg| 39ms| 39ms | 0s | 0.000
| |  P99| 240ms| 241ms | 1ms | 0.417
| ThreadStore.Get |  Avg| 10ms| 9ms | -1ms | -9.688
| |  P99| 116ms| 94ms | -22ms | -19.009
| ThreadStore.GetMembershipForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 93ms | 2ms | 2.187
| ThreadStore.GetTeamsUnreadForUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 111ms| 125ms | 14ms | 12.560
| ThreadStore.GetThreadFollowers |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 80ms| 87ms | 7ms | 8.728
| ThreadStore.GetThreadForUser |  Avg| 17ms| 16ms | -1ms | -6.008
| |  P99| 185ms| 184ms | -1ms | -0.540
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 17ms| 15ms | -2ms | -11.884
| |  P99| 130ms| 97ms | -33ms | -25.428
| ThreadStore.GetThreadsForUser |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 99ms| 119ms | 20ms | 20.193
| ThreadStore.GetTotalThreads |  Avg| 8ms| 7ms | -1ms | -13.247
| |  P99| 87ms| 87ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 85ms| 86ms | 1ms | 1.172
| ThreadStore.GetTotalUnreadThreads |  Avg| 8ms| 7ms | -1ms | -13.292
| |  P99| 85ms| 87ms | 2ms | 2.363
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 85ms| 89ms | 4ms | 4.729
| ThreadStore.MaintainMembership |  Avg| 15ms| 17ms | 2ms | 13.554
| |  P99| 205ms| 216ms | 11ms | 5.365
| ThreadStore.MarkAllAsReadByChannels |  Avg| 7ms| 9ms | 2ms | 28.122
| |  P99| 88ms| 94ms | 6ms | 6.797
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 1ms | -2ms | -72.785
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 7ms| 8ms | 1ms | 13.565
| |  P99| 80ms| 83ms | 3ms | 3.756
| ThreadStore.UpdateMembership |  Avg| 7ms| 8ms | 1ms | 13.948
| |  P99| 82ms| 84ms | 2ms | 2.448
| TokenStore.Cleanup |  Avg| 1ms| 17ms | 16ms | 1097.290
| |  P99| 5ms| 49ms | 44ms | 888.666
| UserAccessTokenStore.GetByToken |  Avg| 7ms| 6ms | -1ms | -14.584
| |  P99| 47ms| 48ms | 1ms | 2.115
| UserStore.AutocompleteUsersInChannel |  Avg| 91ms| 75ms | -16ms | -17.613
| |  P99| 459ms| 361ms | -98ms | -21.352
| UserStore.Count |  Avg| 33ms| 21ms | -12ms | -36.235
| |  P99| 220ms| 93ms | -127ms | -57.727
| UserStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 75ms| 81ms | 6ms | 7.972
| UserStore.GetAllProfiles |  Avg| 7ms| 6ms | -1ms | -15.258
| |  P99| 56ms| 50ms | -6ms | -10.641
| UserStore.GetAllProfilesInChannel |  Avg| 459ms| 455ms | -4ms | -0.871
| |  P99| 2.302s| 2.26s | -42ms | -1.824
| UserStore.GetByUsername |  Avg| 7ms| 13ms | 6ms | 84.926
| |  P99| 79ms| 220ms | 141ms | 178.481
| UserStore.GetForLogin |  Avg| 6ms| 7ms | 1ms | 16.489
| |  P99| 74ms| 84ms | 10ms | 13.477
| UserStore.GetMany |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 45ms | 21ms | 86.598
| UserStore.GetProfileByIds |  Avg| 9ms| 10ms | 1ms | 10.621
| |  P99| 97ms| 99ms | 2ms | 2.068
| UserStore.GetProfilesByUsernames |  Avg| 10ms| 11ms | 1ms | 9.739
| |  P99| 96ms| 100ms | 4ms | 4.179
| UserStore.GetProfilesInChannel |  Avg| 373ms| 93ms | -280ms | -75.119
| |  P99| 980ms| 435ms | -545ms | -55.612
| UserStore.GetUnreadCount |  Avg| 9ms| 8ms | -1ms | -11.520
| |  P99| 88ms| 92ms | 4ms | 4.564
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 35ms| 42ms | 7ms | 19.974
| UserStore.Save |  Avg| 81ms| 84ms | 3ms | 3.689
| |  P99| 276ms| 344ms | 68ms | 24.672
| UserStore.Search |  Avg| 62ms| 54ms | -8ms | -12.930
| |  P99| 249ms| 234ms | -15ms | -6.029
| UserStore.Update |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 244ms| 209ms | -35ms | -14.344
| UserStore.UpdateFailedPasswordAttempts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 76ms| 78ms | 2ms | 2.619
| UserStore.UpdateLastLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 57ms| 65ms | 8ms | 13.922
| UserStore.UpdateUpdateAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 60ms| 63ms | 3ms | 4.987
| UserTermsOfServiceStore.GetByUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 73ms| 80ms | 7ms | 9.557
| WebhookStore.GetOutgoingByTeam |  Avg| 12ms| 13ms | 1ms | 8.056
| |  P99| 108ms| 139ms | 31ms | 28.618
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 448ms| 449ms | 1ms | 0.223
| | P99| 2.8s| 2.292s | -508ms | -18.143
| addTeamMember | Avg| 1.289s| 1.303s | 14ms | 1.086
| | P99| 6.849s| 6.754s | -95ms | -1.387
| autocompleteChannelsForTeamForSearch | Avg| 127ms| 88ms | -39ms | -30.646
| | P99| 4.046s| 2.205s | -1.841s | -45.504
| autocompleteUsers | Avg| 78ms| 65ms | -13ms | -16.590
| | P99| 438ms| 316ms | -122ms | -27.876
| createCategoryForTeamForUser | Avg| 71ms| 43ms | -28ms | -39.408
| | P99| 245ms| 99ms | -146ms | -59.470
| createChannel | Avg| 84ms| 47ms | -37ms | -43.889
| | P99| 475ms| 241ms | -234ms | -49.263
| createDirectChannel | Avg| 435ms| 476ms | 41ms | 9.434
| | P99| 2.232s| 2.361s | 129ms | 5.780
| createGroupChannel | Avg| 733ms| 739ms | 6ms | 0.819
| | P99| 3.733s| 4.375s | 642ms | 17.196
| createPost | Avg| 808ms| 827ms | 19ms | 2.350
| | P99| 4.564s| 4.483s | -81ms | -1.775
| createUser | Avg| 131ms| 240ms | 109ms | 83.173
| | P99| 645ms| 1.709s | 1.064s | 164.902
| deletePost | Avg| 51ms| 117ms | 66ms | 128.591
| | P99| 240ms| 910ms | 670ms | 278.875
| followThreadByUser | Avg| 59ms| 51ms | -8ms | -13.532
| | P99| 830ms| 433ms | -397ms | -47.832
| getAllTeams | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 94ms| 99ms | 5ms | 5.322
| getCategoriesForTeamForUser | Avg| 44ms| 40ms | -4ms | -9.132
| | P99| 237ms| 234ms | -3ms | -1.263
| getChannel | Avg| 17ms| 18ms | 1ms | 5.841
| | P99| 165ms| 192ms | 27ms | 16.351
| getChannelMember | Avg| 18ms| 19ms | 1ms | 5.455
| | P99| 222ms| 223ms | 1ms | 0.450
| getChannelMembers | Avg| 43ms| 4ms | -39ms | -91.310
| | P99| 99ms| 5ms | -94ms | -94.949
| getChannelMembersForTeamForUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 99ms| 105ms | 6ms | 6.091
| getChannelStats | Avg| 10ms| 6ms | -4ms | -41.231
| | P99| 178ms| 97ms | -81ms | -45.607
| getChannelUnread | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 95ms| 152ms | 57ms | 59.797
| getChannelsForTeamForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 100ms| 123ms | 23ms | 23.086
| getChannelsForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 92ms| 127ms | 35ms | 38.011
| getClientConfig | Avg| 14ms| 16ms | 2ms | 14.431
| | P99| 209ms| 226ms | 17ms | 8.136
| getFilePreview | Avg| 65ms| 57ms | -8ms | -12.228
| | P99| 361ms| 302ms | -59ms | -16.361
| getFileThumbnail | Avg| 58ms| 47ms | -11ms | -19.079
| | P99| 314ms| 248ms | -66ms | -21.051
| getPostThread | Avg| 52ms| 49ms | -3ms | -5.739
| | P99| 452ms| 451ms | -1ms | -0.221
| getPostsForChannel | Avg| 97ms| 92ms | -5ms | -5.168
| | P99| 962ms| 955ms | -7ms | -0.728
| getPostsForChannelAroundLastUnread | Avg| 41ms| 41ms | 0s | 0.000
| | P99| 439ms| 452ms | 13ms | 2.958
| getPreferences | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 92ms| 95ms | 3ms | 3.272
| getPrevTrialLicense | Avg| 1ms| 4ms | 3ms | 284.210
| | P99| 5ms| 24ms | 19ms | 383.838
| getProfileImage | Avg| 80ms| 86ms | 6ms | 7.488
| | P99| 464ms| 478ms | 14ms | 3.018
| getPublicChannelsForTeam | Avg| 37ms| 32ms | -5ms | -13.597
| | P99| 237ms| 212ms | -25ms | -10.536
| getTeamMember | Avg| 9ms| 10ms | 1ms | 11.529
| | P99| 94ms| 131ms | 37ms | 39.162
| getTeamMembersForUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 96ms| 110ms | 14ms | 14.590
| getTeamsForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 84ms| 84ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 178ms| 193ms | 15ms | 8.425
| getThreadsForUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 118ms| 143ms | 25ms | 21.249
| getUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 204ms| 215ms | 11ms | 5.393
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 2ms | 1ms | 75.163
| | P99| 21ms| 25ms | 4ms | 19.173
| getUsers | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 205ms| 203ms | -2ms | -0.978
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 34ms| 38ms | 4ms | 11.929
| getUsersByNames | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 97ms| 117ms | 20ms | 20.563
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 153ms| 164ms | 11ms | 7.195
| | P99| 987ms| 1.34s | 353ms | 35.752
| logout | Avg| 163ms| 152ms | -11ms | -6.756
| | P99| 885ms| 480ms | -405ms | -45.765
| patchPost | Avg| 140ms| 599ms | 459ms | 327.894
| | P99| 3.038s| 2.2s | -838ms | -27.586
| removeUserCustomStatus | Avg| 316ms| 351ms | 35ms | 11.076
| | P99| 973ms| 2.02s | 1.047s | 107.554
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 33ms| 34ms | 1ms | 2.987
| | P99| 243ms| 248ms | 5ms | 2.058
| searchAllChannels | Avg| 68ms| 59ms | -9ms | -13.325
| | P99| 283ms| 240ms | -43ms | -15.172
| searchGroupChannels | Avg| 19ms| 18ms | -1ms | -5.234
| | P99| 118ms| 142ms | 24ms | 20.287
| searchPostsInTeam | Avg| 314ms| 273ms | -41ms | -13.074
| | P99| 3.724s| 2.439s | -1.285s | -34.508
| searchUsers | Avg| 64ms| 56ms | -8ms | -12.427
| | P99| 250ms| 237ms | -13ms | -5.200
| setPostReminder | Avg| 60ms| 54ms | -6ms | -10.058
| | P99| 244ms| 433ms | 189ms | 77.538
| unfollowThreadByUser | Avg| 48ms| 54ms | 6ms | 12.600
| | P99| 381ms| 427ms | 46ms | 12.079
| updateCategoriesForTeamForUser | Avg| 186ms| 132ms | -54ms | -29.042
| | P99| 1.84s| 898ms | -942ms | -51.197
| updatePreferences | Avg| 28ms| 36ms | 8ms | 28.839
| | P99| 250ms| 372ms | 122ms | 48.819
| updateReadStateAllThreadsByUser | Avg| 3ms| 1ms | -2ms | -69.825
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 123ms| 119ms | -4ms | -3.251
| | P99| 864ms| 859ms | -5ms | -0.578
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 458ms| 484ms | 26ms | 5.683
| | P99| 1.945s| 2.143s | 198ms | 10.181
| upsertDraft | Avg| 3ms| 29ms | 26ms | 866.754
| | P99| 5ms| 243ms | 238ms | 4804.269
| viewChannel | Avg| 34ms| 38ms | 4ms | 11.752
| | P99| 363ms| 401ms | 38ms | 10.462
