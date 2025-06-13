### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | avg | 0s | 50ms | 50ms | 14430194.26
| PostStore.GetPostsByIds | avg | 3ms | 13ms | 10ms | 398.09
| RoleStore.ChannelHigherScopedPermissions | avg | 6ms | 28ms | 22ms | 368.07
| ChannelStore.GetChannelsByIds | avg | 2ms | 9ms | 7ms | 335.41
| PostPersistentNotificationStore.UpdateLastActivity | avg | 5ms | 22ms | 17ms | 314.24
| TeamStore.GetMany | avg | 5ms | 20ms | 15ms | 290.76
| TokenStore.Cleanup | avg | 8ms | 27ms | 19ms | 240.13
| CommandWebhookStore.Cleanup | avg | 8ms | 25ms | 17ms | 220.28
| EmojiStore.GetMultipleByName | avg | 7ms | 15ms | 8ms | 122.60
| BotStore.Get | avg | 6ms | 12ms | 6ms | 95.30
| PostPersistentNotificationStore.DeleteExpired | avg | 4ms | 8ms | 4ms | 90.19
| PostStore.GetPostReminders | avg | 14ms | 25ms | 11ms | 77.25
| UserStore.Count | avg | 17ms | 28ms | 11ms | 66.43
| StatusStore.Get | avg | 5ms | 8ms | 3ms | 62.49
| PostPersistentNotificationStore.Get | avg | 5ms | 8ms | 3ms | 59.74
| UserStore.GetMany | avg | 5ms | 8ms | 3ms | 55.48
| UserStore.Get | avg | 6ms | 9ms | 3ms | 49.51
| PostStore.Delete | avg | 32ms | 44ms | 12ms | 37.85
| UserStore.GetByUsername | avg | 10ms | 13ms | 3ms | 30.69
| ChannelStore.UpdateSidebarCategories | avg | 72ms | 91ms | 19ms | 26.42
| FileInfoStore.GetByIds | avg | 8ms | 10ms | 2ms | 23.77
| ChannelStore.GetAllChannelMembersForUser | avg | 10ms | 12ms | 2ms | 21.00
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 20ms | 24ms | 4ms | 19.58
| TeamStore.GetTotalMemberCount | avg | 51ms | 60ms | 9ms | 17.71
| JobStore.GetAllByStatus | avg | 11ms | 13ms | 2ms | 17.56
| StatusStore.GetByIds | avg | 12ms | 14ms | 2ms | 17.34
| ProductNoticesStore.ClearOldNotices | avg | 24ms | 28ms | 4ms | 16.40
| ClusterDiscoveryStore.SetLastPingAt | avg | 12ms | 14ms | 2ms | 16.40
| TeamStore.GetActiveMemberCount | avg | 56ms | 64ms | 8ms | 14.34
| ChannelStore.CreateDirectChannel | avg | 60ms | 68ms | 8ms | 13.28
| UserStore.Search | avg | 27ms | 30ms | 3ms | 10.96
| PostStore.SearchPostsForUser | avg | 65ms | 71ms | 6ms | 9.28
| UserStore.AutocompleteUsersInChannel | avg | 63ms | 68ms | 5ms | 7.95
| ChannelStore.GetPublicChannelsForTeam | avg | 25ms | 27ms | 2ms | 7.88
| ChannelStore.GetMemberCount | avg | 28ms | 30ms | 2ms | 7.27
| ChannelStore.CreateInitialSidebarCategories | avg | 34ms | 36ms | 2ms | 5.85
| ChannelStore.SaveMember | avg | 45ms | 47ms | 2ms | 4.47
| ProductNoticesStore.View | avg | 58ms | 60ms | 2ms | 3.44
| UserStore.Save | avg | 87ms | 89ms | 2ms | 2.29
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | p99 | 5ms | 246ms | 241ms | 4868.67
| ChannelStore.GetChannelsByIds | p99 | 5ms | 48ms | 43ms | 868.35
| RoleStore.ChannelHigherScopedPermissions | p99 | 25ms | 224ms | 199ms | 805.67
| PostStore.GetPostsByIds | p99 | 10ms | 49ms | 39ms | 397.96
| UserStore.Count | p99 | 48ms | 216ms | 168ms | 348.19
| CommandWebhookStore.Cleanup | p99 | 25ms | 99ms | 74ms | 301.43
| TokenStore.Cleanup | p99 | 25ms | 99ms | 74ms | 301.42
| BotStore.Get | p99 | 47ms | 188ms | 141ms | 300.53
| TeamStore.GetMany | p99 | 24ms | 96ms | 72ms | 296.55
| PostStore.GetPostReminders | p99 | 82ms | 219ms | 137ms | 168.10
| TeamStore.GetActiveMemberCount | p99 | 99ms | 208ms | 109ms | 109.84
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 24ms | 49ms | 25ms | 102.45
| PostPersistentNotificationStore.Get | p99 | 44ms | 88ms | 44ms | 99.06
| ClusterDiscoveryStore.SetLastPingAt | p99 | 98ms | 181ms | 83ms | 84.61
| UserStore.GetByUsername | p99 | 99ms | 176ms | 77ms | 77.73
| PostStore.Delete | p99 | 232ms | 412ms | 180ms | 77.42
| ChannelStore.UpdateSidebarCategories | p99 | 413ms | 717ms | 304ms | 73.70
| TeamStore.GetMember | p99 | 40ms | 69ms | 29ms | 72.33
| FileInfoStore.GetByIds | p99 | 89ms | 145ms | 56ms | 63.16
| StatusStore.Get | p99 | 67ms | 96ms | 29ms | 43.10
| ChannelStore.GetChannelsByUser | p99 | 63ms | 86ms | 23ms | 36.76
| ThreadStore.Get | p99 | 63ms | 86ms | 23ms | 36.58
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 50ms | 64ms | 14ms | 27.95
| ChannelStore.GetChannelUnread | p99 | 102ms | 130ms | 28ms | 27.41
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 67ms | 84ms | 17ms | 25.29
| ChannelStore.GetMembersForUser | p99 | 99ms | 124ms | 25ms | 25.15
| LinkMetadataStore.Save | p99 | 72ms | 90ms | 18ms | 24.83
| FileInfoStore.AttachToPost | p99 | 138ms | 171ms | 33ms | 23.89
| PostStore.SearchPostsForUser | p99 | 2.019s | 2.488s | 469ms | 23.22
| PostStore.GetEtag | p99 | 99ms | 121ms | 22ms | 22.14
| ChannelStore.GetChannels | p99 | 114ms | 138ms | 24ms | 21.09
| ChannelStore.GetAllChannelMembersForUser | p99 | 91ms | 110ms | 19ms | 20.94
| UserStore.GetAllProfiles | p99 | 52ms | 62ms | 10ms | 19.17
| SessionStore.GetLRUSessions | p99 | 53ms | 63ms | 10ms | 18.96
| PostPersistentNotificationStore.DeleteExpired | p99 | 70ms | 83ms | 13ms | 18.70
| FileInfoStore.Get | p99 | 102ms | 121ms | 19ms | 18.63
| StatusStore.GetByIds | p99 | 152ms | 180ms | 28ms | 18.37
| ChannelStore.SearchGroupChannels | p99 | 128ms | 150ms | 22ms | 17.19
| ChannelStore.GetMemberCount | p99 | 166ms | 194ms | 28ms | 16.85
| ChannelStore.GetMemberLastViewedAt | p99 | 68ms | 79ms | 11ms | 16.20
| PostStore.GetPosts | p99 | 58ms | 67ms | 9ms | 15.60
| DraftStore.Upsert | p99 | 100ms | 115ms | 15ms | 15.02
| ChannelStore.GetMembersForUserWithPagination | p99 | 73ms | 84ms | 11ms | 15.02
| UserStore.Get | p99 | 84ms | 96ms | 12ms | 14.23
| ChannelStore.CreateInitialSidebarCategories | p99 | 318ms | 359ms | 41ms | 12.89
| ChannelStore.GetSidebarCategory | p99 | 198ms | 223ms | 25ms | 12.66
| UserStore.GetUnreadCount | p99 | 80ms | 90ms | 10ms | 12.50
| ChannelStore.Get | p99 | 154ms | 173ms | 19ms | 12.30
| UserTermsOfServiceStore.GetByUser | p99 | 73ms | 82ms | 9ms | 12.30
| SessionStore.Save | p99 | 98ms | 110ms | 12ms | 12.22
| UserStore.IsEmpty | p99 | 36ms | 40ms | 4ms | 11.17
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 81ms | 90ms | 9ms | 11.16
| TeamStore.GetTotalMemberCount | p99 | 206ms | 229ms | 23ms | 11.14
| ChannelStore.GetMember | p99 | 83ms | 92ms | 9ms | 10.79
| ThreadStore.GetThreadsForUser | p99 | 131ms | 145ms | 14ms | 10.66
| TeamStore.GetTeamsByUserId | p99 | 77ms | 85ms | 8ms | 10.43
| TeamStore.GetTeamsForUser | p99 | 77ms | 85ms | 8ms | 10.34
| JobStore.GetNewestJobByStatusesAndType | p99 | 79ms | 87ms | 8ms | 10.10
| TeamStore.GetAllPage | p99 | 79ms | 87ms | 8ms | 10.09
| ThreadStore.GetTotalUnreadThreads | p99 | 79ms | 87ms | 8ms | 10.08
| ThreadStore.GetTotalUnreadMentions | p99 | 80ms | 88ms | 8ms | 10.01
| DraftStore.Get | p99 | 141ms | 155ms | 14ms | 9.96
| SystemStore.GetByName | p99 | 71ms | 78ms | 7ms | 9.82
| UserStore.GetProfilesByUsernames | p99 | 122ms | 134ms | 12ms | 9.81
| GroupStore.GetByName | p99 | 76ms | 83ms | 7ms | 9.23
| ChannelStore.Save | p99 | 341ms | 372ms | 31ms | 9.08
| PostStore.GetPostsBefore | p99 | 122ms | 133ms | 11ms | 9.05
| UserStore.GetProfileByIds | p99 | 111ms | 121ms | 10ms | 9.02
| ThreadStore.GetTotalThreads | p99 | 80ms | 87ms | 7ms | 8.78
| ChannelStore.GetPublicChannelsForTeam | p99 | 195ms | 212ms | 17ms | 8.72
| PreferenceStore.GetAll | p99 | 83ms | 90ms | 7ms | 8.43
| ThreadStore.GetTeamsUnreadForUser | p99 | 97ms | 105ms | 8ms | 8.29
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 82ms | 88ms | 6ms | 7.32
| EmojiStore.GetByName | p99 | 85ms | 91ms | 6ms | 7.05
| ChannelStore.GetGuestCount | p99 | 87ms | 93ms | 6ms | 6.91
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 203ms | 217ms | 14ms | 6.91
| PostStore.GetPostsSince | p99 | 191ms | 204ms | 13ms | 6.81
| ChannelStore.GetByName | p99 | 89ms | 95ms | 6ms | 6.72
| UserStore.GetForLogin | p99 | 77ms | 82ms | 5ms | 6.51
| UserStore.Search | p99 | 206ms | 219ms | 13ms | 6.32
| UserStore.UpdateFailedPasswordAttempts | p99 | 79ms | 84ms | 5ms | 6.30
| PostStore.GetPostIdAfterTime | p99 | 49ms | 52ms | 3ms | 6.11
| ChannelStore.SaveMember | p99 | 363ms | 384ms | 21ms | 5.78
| FileInfoStore.Save | p99 | 142ms | 150ms | 8ms | 5.65
| PostStore.GetPostsByThread | p99 | 91ms | 96ms | 5ms | 5.48
| UserStore.Update | p99 | 207ms | 218ms | 11ms | 5.32
| ChannelStore.IncrementMentionCount | p99 | 87ms | 91ms | 4ms | 4.62
| ChannelStore.GetMemberForPost | p99 | 153ms | 160ms | 7ms | 4.57
| PostPriorityStore.GetForPosts | p99 | 156ms | 163ms | 7ms | 4.50
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 93ms | 97ms | 4ms | 4.29
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 48ms | 50ms | 2ms | 4.20
| WebhookStore.GetOutgoingByTeam | p99 | 144ms | 150ms | 6ms | 4.16
| PostAcknowledgementStore.GetForPosts | p99 | 147ms | 153ms | 6ms | 4.09
| ThreadStore.GetThreadFollowers | p99 | 78ms | 81ms | 3ms | 3.85
| AuditStore.Save | p99 | 78ms | 81ms | 3ms | 3.84
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 84ms | 87ms | 3ms | 3.57
| ThreadStore.GetThreadForUser | p99 | 171ms | 177ms | 6ms | 3.51
| DraftStore.Delete | p99 | 95ms | 98ms | 3ms | 3.14
| TeamStore.Get | p99 | 79ms | 81ms | 2ms | 2.53
| PostStore.GetSingle | p99 | 83ms | 85ms | 2ms | 2.40
| GroupStore.GetGroups | p99 | 87ms | 89ms | 2ms | 2.31
| LinkMetadataStore.Get | p99 | 87ms | 89ms | 2ms | 2.30
| ThreadStore.MarkAllAsReadByChannels | p99 | 88ms | 90ms | 2ms | 2.26
| UserStore.Save | p99 | 319ms | 325ms | 6ms | 1.88
| PostStore.Get | p99 | 222ms | 226ms | 4ms | 1.80
| TeamStore.SaveMember | p99 | 227ms | 231ms | 4ms | 1.76
| ChannelStore.AutocompleteInTeamForSearch | p99 | 238ms | 242ms | 4ms | 1.68
| JobStore.GetAllByStatus | p99 | 148ms | 150ms | 2ms | 1.35
| ProductNoticesStore.View | p99 | 463ms | 468ms | 5ms | 1.08
| FileInfoStore.SetContent | p99 | 186ms | 188ms | 2ms | 1.08
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PluginStore.Get | avg | 2ms | 0s | -2ms | -132.03
| JobStore.Get | avg | 7ms | 0s | -7ms | -103.73
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 23ms | 0s | -23ms | -98.30
| ChannelStore.CreateSidebarCategory | avg | 101ms | 45ms | -56ms | -55.23
| SessionStore.Remove | avg | 10ms | 5ms | -5ms | -52.62
| PreferenceStore.DeleteCategoryAndName | avg | 16ms | 9ms | -7ms | -44.10
| PostPriorityStore.GetForPost | avg | 8ms | 5ms | -3ms | -39.37
| ChannelStore.GetMembers | avg | 8ms | 5ms | -3ms | -39.10
| UserStore.GetProfilesNotInChannel | avg | 18ms | 12ms | -6ms | -34.07
| JobStore.Save | avg | 11ms | 8ms | -3ms | -28.19
| PostStore.GetPostReminderMetadata | avg | 11ms | 8ms | -3ms | -26.47
| PluginStore.List | avg | 12ms | 9ms | -3ms | -26.03
| UserStore.GetProfilesInChannel | avg | 20ms | 15ms | -5ms | -24.85
| ChannelStore.GetTeamChannels | avg | 46ms | 35ms | -11ms | -23.94
| PostStore.SetPostReminder | avg | 21ms | 16ms | -5ms | -23.80
| ThreadStore.MarkAllAsReadByTeam | avg | 14ms | 11ms | -3ms | -21.19
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 22ms | 19ms | -3ms | -13.36
| StatusStore.SaveOrUpdate | avg | 22ms | 19ms | -3ms | -13.35
| ChannelStore.AutocompleteInTeamForSearch | avg | 55ms | 51ms | -4ms | -7.28
| UserStore.GetAllProfilesInChannel | avg | 338ms | 326ms | -12ms | -3.55
| PostStore.AnalyticsPostCount | avg | 306ms | 299ms | -7ms | -2.29
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PluginStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| JobStore.Get | p99 | 100ms | 0s | -100ms | -100.24
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 173ms | 0s | -173ms | -100.07
| ChannelStore.CreateSidebarCategory | p99 | 483ms | 99ms | -384ms | -79.59
| PostStore.GetPostReminderMetadata | p99 | 145ms | 53ms | -92ms | -63.45
| SessionStore.Remove | p99 | 84ms | 34ms | -50ms | -59.35
| PreferenceStore.DeleteCategoryAndName | p99 | 198ms | 83ms | -115ms | -58.23
| JobStore.Save | p99 | 173ms | 72ms | -101ms | -58.21
| UserStore.GetProfilesNotInChannel | p99 | 206ms | 86ms | -120ms | -58.11
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 197ms | 83ms | -114ms | -57.72
| ChannelStore.GetMembers | p99 | 48ms | 24ms | -24ms | -49.61
| ThreadStore.MarkAllAsReadByTeam | p99 | 95ms | 48ms | -47ms | -49.47
| UserAccessTokenStore.GetByToken | p99 | 151ms | 83ms | -68ms | -45.04
| JobStore.GetCountByStatusAndType | p99 | 172ms | 99ms | -73ms | -42.44
| JobStore.UpdateStatusOptimistically | p99 | 83ms | 50ms | -33ms | -39.68
| PostPriorityStore.GetForPost | p99 | 94ms | 65ms | -29ms | -30.77
| PostAcknowledgementStore.GetForPost | p99 | 63ms | 47ms | -16ms | -25.44
| StatusStore.SaveOrUpdate | p99 | 346ms | 285ms | -61ms | -17.65
| UserStore.GetProfilesInChannel | p99 | 224ms | 188ms | -36ms | -16.04
| PostStore.GetPostsAfter | p99 | 109ms | 92ms | -17ms | -15.55
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 250ms | 214ms | -36ms | -14.40
| JobStore.UpdateOptimistically | p99 | 50ms | 43ms | -7ms | -14.02
| UserStore.GetMany | p99 | 77ms | 70ms | -7ms | -9.09
| PostStore.SetPostReminder | p99 | 196ms | 180ms | -16ms | -8.16
| PluginStore.List | p99 | 136ms | 127ms | -9ms | -6.62
| UserStore.UpdateLastLogin | p99 | 53ms | 50ms | -3ms | -5.62
| PostStore.Save | p99 | 268ms | 253ms | -15ms | -5.59
| DraftStore.GetDraftsForUser | p99 | 141ms | 135ms | -6ms | -4.27
| ChannelStore.GetTeamChannels | p99 | 239ms | 229ms | -10ms | -4.18
| StatusStore.UpdateExpiredDNDStatuses | p99 | 195ms | 189ms | -6ms | -3.08
| PostStore.Update | p99 | 185ms | 180ms | -5ms | -2.71
| ReactionStore.GetForPost | p99 | 77ms | 75ms | -2ms | -2.61
| SessionStore.Get | p99 | 192ms | 187ms | -5ms | -2.61
| ThreadStore.MaintainMembership | p99 | 205ms | 200ms | -5ms | -2.44
| UserStore.GetAllProfilesInChannel | p99 | 1.665s | 1.626s | -39ms | -2.34
| ChannelStore.GetPinnedPostCount | p99 | 96ms | 94ms | -2ms | -2.07
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deletePost | avg | 56ms | 76ms | 20ms | 35.79
| getChannelMembersForUser | avg | 6ms | 8ms | 2ms | 31.06
| viewChannel | avg | 36ms | 45ms | 9ms | 24.91
| followThreadByUser | avg | 44ms | 52ms | 8ms | 18.07
| updateCategoriesForTeamForUser | avg | 117ms | 138ms | 21ms | 17.88
| getCategoriesForTeamForUser | avg | 21ms | 24ms | 3ms | 14.00
| searchPostsInTeam | avg | 83ms | 91ms | 8ms | 9.66
| autocompleteUsers | avg | 56ms | 60ms | 4ms | 7.15
| searchUsers | avg | 29ms | 31ms | 2ms | 6.93
| saveReaction | avg | 31ms | 33ms | 2ms | 6.39
| getPostsForChannelAroundLastUnread | avg | 33ms | 35ms | 2ms | 6.08
| getPostsForChannel | avg | 89ms | 94ms | 5ms | 5.61
| getPostThread | avg | 48ms | 50ms | 2ms | 4.14
| getFileThumbnail | avg | 52ms | 54ms | 2ms | 3.81
| getFilePreview | avg | 61ms | 63ms | 2ms | 3.28
| uploadFileStream | avg | 564ms | 572ms | 8ms | 1.42
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deletePost | p99 | 239ms | 456ms | 217ms | 90.61
| updateCategoriesForTeamForUser | p99 | 650ms | 919ms | 269ms | 41.38
| getTeamMember | p99 | 100ms | 136ms | 36ms | 36.03
| getChannelsForUser | p99 | 66ms | 87ms | 21ms | 31.63
| viewChannel | p99 | 357ms | 429ms | 72ms | 20.15
| searchPostsInTeam | p99 | 2.082s | 2.489s | 407ms | 19.55
| getChannelMembersForTeamForUser | p99 | 110ms | 130ms | 20ms | 18.21
| getUserStatusesByIds | p99 | 42ms | 49ms | 7ms | 16.80
| removeUserCustomStatus | p99 | 1.205s | 1.405s | 200ms | 16.60
| getPublicChannelsForTeam | p99 | 195ms | 218ms | 23ms | 11.80
| getChannelMembersForUser | p99 | 77ms | 85ms | 8ms | 10.36
| getChannelsForTeamForUser | p99 | 130ms | 143ms | 13ms | 10.02
| getUsers | p99 | 166ms | 179ms | 13ms | 7.85
| setPostReminder | p99 | 410ms | 441ms | 31ms | 7.56
| getTeamsForUser | p99 | 80ms | 86ms | 6ms | 7.55
| listChannelBookmarksForChannel | p99 | 99ms | 106ms | 7ms | 7.07
| getFilePreview | p99 | 301ms | 322ms | 21ms | 6.98
| getUser | p99 | 178ms | 190ms | 12ms | 6.74
| searchGroupChannels | p99 | 142ms | 151ms | 9ms | 6.35
| upsertDraft | p99 | 175ms | 186ms | 11ms | 6.28
| getPreferences | p99 | 87ms | 92ms | 5ms | 5.75
| deleteDraft | p99 | 161ms | 170ms | 9ms | 5.59
| searchUsers | p99 | 211ms | 222ms | 11ms | 5.21
| getTeamsUnreadForUser | p99 | 185ms | 194ms | 9ms | 4.87
| getCategoriesForTeamForUser | p99 | 212ms | 222ms | 10ms | 4.73
| getThreadsForUser | p99 | 150ms | 157ms | 7ms | 4.66
| getTeamMembersForUser | p99 | 89ms | 93ms | 4ms | 4.48
| getAllTeams | p99 | 94ms | 98ms | 4ms | 4.27
| getPostsForChannelAroundLastUnread | p99 | 355ms | 368ms | 13ms | 3.66
| getChannelStats | p99 | 92ms | 95ms | 3ms | 3.27
| getPostsForChannel | p99 | 893ms | 915ms | 22ms | 2.46
| getUsersByNames | p99 | 142ms | 145ms | 3ms | 2.12
| getChannelMember | p99 | 200ms | 204ms | 4ms | 2.00
| getClientConfig | p99 | 211ms | 215ms | 4ms | 1.89
| getChannelUnread | p99 | 160ms | 163ms | 3ms | 1.88
| createChannel | p99 | 2.355s | 2.395s | 40ms | 1.70
| autocompleteChannelsForTeamForSearch | p99 | 238ms | 242ms | 4ms | 1.68
| saveReaction | p99 | 242ms | 246ms | 4ms | 1.65
| uploadFileStream | p99 | 2.233s | 2.261s | 28ms | 1.25
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createEmoji | avg | 7ms | 0s | -7ms | -105.72
| login | avg | 228ms | 99ms | -129ms | -56.59
| createCategoryForTeamForUser | avg | 110ms | 50ms | -60ms | -54.78
| logout | avg | 164ms | 93ms | -71ms | -43.34
| patchPost | avg | 113ms | 70ms | -43ms | -37.96
| getChannel | avg | 29ms | 18ms | -11ms | -37.82
| getChannelMembers | avg | 10ms | 7ms | -3ms | -30.23
| createGroupChannel | avg | 1.06s | 827ms | -233ms | -21.98
| updateReadStateAllThreadsByUser | avg | 14ms | 11ms | -3ms | -21.03
| createPost | avg | 674ms | 563ms | -111ms | -16.46
| createChannel | avg | 654ms | 558ms | -96ms | -14.68
| createDirectChannel | avg | 624ms | 536ms | -88ms | -14.10
| getProfileImage | avg | 80ms | 69ms | -11ms | -13.75
| addChannelMember | avg | 523ms | 458ms | -65ms | -12.42
| getTeamStats | avg | 81ms | 71ms | -10ms | -12.40
| createUser | avg | 283ms | 252ms | -31ms | -10.95
| autocompleteChannelsForTeamForSearch | avg | 55ms | 51ms | -4ms | -7.27
| removeUserCustomStatus | avg | 360ms | 335ms | -25ms | -6.95
| updatePreferences | avg | 36ms | 34ms | -2ms | -5.55
| updateReadStateThreadByUser | avg | 117ms | 114ms | -3ms | -2.57
| addTeamMember | avg | 1.049s | 1.028s | -21ms | -2.00
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createEmoji | p99 | 10ms | 0s | -10ms | -100.50
| createCategoryForTeamForUser | p99 | 483ms | 99ms | -384ms | -79.59
| login | p99 | 2.262s | 628ms | -1.634s | -72.25
| patchPost | p99 | 1.3s | 599ms | -701ms | -53.92
| getChannelMembers | p99 | 48ms | 24ms | -24ms | -49.61
| updateReadStateAllThreadsByUser | p99 | 95ms | 48ms | -47ms | -49.47
| getTeamStats | p99 | 428ms | 229ms | -199ms | -46.55
| createPost | p99 | 3.664s | 2.76s | -904ms | -24.67
| createUser | p99 | 1.838s | 1.449s | -389ms | -21.17
| getChannel | p99 | 249ms | 197ms | -52ms | -20.90
| updatePreferences | p99 | 344ms | 294ms | -50ms | -14.54
| logout | p99 | 487ms | 419ms | -68ms | -13.97
| createGroupChannel | p99 | 4.45s | 4.054s | -396ms | -8.90
| followThreadByUser | p99 | 472ms | 433ms | -39ms | -8.27
| updateReadStateThreadByUser | p99 | 762ms | 705ms | -57ms | -7.48
| unfollowThreadByUser | p99 | 391ms | 368ms | -23ms | -5.88
| getUsersByIds | p99 | 43ms | 41ms | -2ms | -4.64
| addChannelMember | p99 | 2.374s | 2.271s | -103ms | -4.34
| getDrafts | p99 | 166ms | 161ms | -5ms | -3.02
| getProfileImage | p99 | 477ms | 465ms | -12ms | -2.52
| createDirectChannel | p99 | 2.433s | 2.407s | -26ms | -1.07
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 78ms| 81ms | 3ms | 3.844
| BotStore.Get |  Avg| 6ms| 12ms | 6ms | 95.301
| |  P99| 47ms| 188ms | 141ms | 300.533
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 93ms| 97ms | 4ms | 4.285
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 48ms| 50ms | 2ms | 4.202
| ChannelStore.Autocomplete |  Avg| 45ms| 46ms | 1ms | 2.220
| |  P99| 223ms| 224ms | 1ms | 0.448
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 55ms| 51ms | -4ms | -7.279
| |  P99| 238ms| 242ms | 4ms | 1.678
| ChannelStore.CreateDirectChannel |  Avg| 60ms| 68ms | 8ms | 13.276
| |  P99| 475ms| 479ms | 4ms | 0.843
| ChannelStore.CreateInitialSidebarCategories |  Avg| 34ms| 36ms | 2ms | 5.851
| |  P99| 318ms| 359ms | 41ms | 12.889
| ChannelStore.CreateSidebarCategory |  Avg| 101ms| 45ms | -56ms | -55.235
| |  P99| 483ms| 99ms | -384ms | -79.585
| ChannelStore.Get |  Avg| 14ms| 15ms | 1ms | 7.261
| |  P99| 154ms| 173ms | 19ms | 12.304
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 23ms| 0s | -23ms | -98.303
| |  P99| 173ms| 0s | -173ms | -100.072
| ChannelStore.GetAllChannelMembersForUser |  Avg| 10ms| 12ms | 2ms | 20.997
| |  P99| 91ms| 110ms | 19ms | 20.941
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 22ms| 19ms | -3ms | -13.359
| |  P99| 250ms| 214ms | -36ms | -14.404
| ChannelStore.GetByName |  Avg| 9ms| 10ms | 1ms | 11.065
| |  P99| 89ms| 95ms | 6ms | 6.720
| ChannelStore.GetChannelUnread |  Avg| 10ms| 11ms | 1ms | 9.960
| |  P99| 102ms| 130ms | 28ms | 27.413
| ChannelStore.GetChannels |  Avg| 11ms| 12ms | 1ms | 9.419
| |  P99| 114ms| 138ms | 24ms | 21.088
| ChannelStore.GetChannelsByIds |  Avg| 2ms| 9ms | 7ms | 335.409
| |  P99| 5ms| 48ms | 43ms | 868.351
| ChannelStore.GetChannelsByUser |  Avg| 5ms| 6ms | 1ms | 19.089
| |  P99| 63ms| 86ms | 23ms | 36.757
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 93ms| 93ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 10ms| 11ms | 1ms | 9.672
| |  P99| 97ms| 96ms | -1ms | -1.036
| ChannelStore.GetGuestCount |  Avg| 7ms| 8ms | 1ms | 13.812
| |  P99| 87ms| 93ms | 6ms | 6.908
| ChannelStore.GetMember |  Avg| 7ms| 8ms | 1ms | 14.203
| |  P99| 83ms| 92ms | 9ms | 10.788
| ChannelStore.GetMemberCount |  Avg| 28ms| 30ms | 2ms | 7.271
| |  P99| 166ms| 194ms | 28ms | 16.854
| ChannelStore.GetMemberForPost |  Avg| 14ms| 15ms | 1ms | 7.041
| |  P99| 153ms| 160ms | 7ms | 4.568
| ChannelStore.GetMemberLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 68ms| 79ms | 11ms | 16.198
| ChannelStore.GetMembers |  Avg| 8ms| 5ms | -3ms | -39.098
| |  P99| 48ms| 24ms | -24ms | -49.612
| ChannelStore.GetMembersForUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 99ms| 124ms | 25ms | 25.146
| ChannelStore.GetMembersForUserWithPagination |  Avg| 6ms| 7ms | 1ms | 16.198
| |  P99| 73ms| 84ms | 11ms | 15.019
| ChannelStore.GetPinnedPostCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 96ms| 94ms | -2ms | -2.075
| ChannelStore.GetPublicChannelsForTeam |  Avg| 25ms| 27ms | 2ms | 7.884
| |  P99| 195ms| 212ms | 17ms | 8.723
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 20ms| 24ms | 4ms | 19.583
| |  P99| 203ms| 217ms | 14ms | 6.907
| ChannelStore.GetSidebarCategory |  Avg| 19ms| 20ms | 1ms | 5.148
| |  P99| 198ms| 223ms | 25ms | 12.658
| ChannelStore.GetTeamChannels |  Avg| 46ms| 35ms | -11ms | -23.944
| |  P99| 239ms| 229ms | -10ms | -4.182
| ChannelStore.IncrementMentionCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 87ms| 91ms | 4ms | 4.616
| ChannelStore.Save |  Avg| 44ms| 45ms | 1ms | 2.296
| |  P99| 341ms| 372ms | 31ms | 9.078
| ChannelStore.SaveMember |  Avg| 45ms| 47ms | 2ms | 4.472
| |  P99| 363ms| 384ms | 21ms | 5.783
| ChannelStore.SearchGroupChannels |  Avg| 13ms| 14ms | 1ms | 7.929
| |  P99| 128ms| 150ms | 22ms | 17.193
| ChannelStore.UpdateLastViewedAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 87ms| 86ms | -1ms | -1.144
| ChannelStore.UpdateSidebarCategories |  Avg| 72ms| 91ms | 19ms | 26.421
| |  P99| 413ms| 717ms | 304ms | 73.695
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 84ms| 87ms | 3ms | 3.566
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 12ms| 14ms | 2ms | 16.403
| |  P99| 98ms| 181ms | 83ms | 84.611
| CommandWebhookStore.Cleanup |  Avg| 8ms| 25ms | 17ms | 220.275
| |  P99| 25ms| 99ms | 74ms | 301.426
| DesktopTokensStore.DeleteOlderThan |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 10ms| 11ms | 1ms | 9.537
| |  P99| 95ms| 98ms | 3ms | 3.144
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 16ms| 15ms | -1ms | -6.240
| |  P99| 197ms| 83ms | -114ms | -57.724
| DraftStore.Get |  Avg| 12ms| 13ms | 1ms | 8.472
| |  P99| 141ms| 155ms | 14ms | 9.964
| DraftStore.GetDraftsForUser |  Avg| 12ms| 13ms | 1ms | 8.437
| |  P99| 141ms| 135ms | -6ms | -4.266
| DraftStore.Upsert |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 100ms| 115ms | 15ms | 15.021
| EmojiStore.GetByName |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 85ms| 91ms | 6ms | 7.054
| EmojiStore.GetMultipleByName |  Avg| 7ms| 15ms | 8ms | 122.600
| |  P99| 48ms| 49ms | 1ms | 2.067
| FileInfoStore.AttachToPost |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 138ms| 171ms | 33ms | 23.894
| FileInfoStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 102ms| 121ms | 19ms | 18.634
| FileInfoStore.GetByIds |  Avg| 8ms| 10ms | 2ms | 23.772
| |  P99| 89ms| 145ms | 56ms | 63.163
| FileInfoStore.GetForPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 95ms| 95ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 13ms| 14ms | 1ms | 7.586
| |  P99| 142ms| 150ms | 8ms | 5.646
| FileInfoStore.SetContent |  Avg| 18ms| 19ms | 1ms | 5.468
| |  P99| 186ms| 188ms | 2ms | 1.077
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 4ms| 5ms | 1ms | 23.900
| |  P99| 50ms| 64ms | 14ms | 27.951
| GroupStore.GetByName |  Avg| 5ms| 6ms | 1ms | 18.683
| |  P99| 76ms| 83ms | 7ms | 9.233
| GroupStore.GetGroups |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 87ms| 89ms | 2ms | 2.308
| JobStore.Get |  Avg| 7ms| 0s | -7ms | -103.726
| |  P99| 100ms| 0s | -100ms | -100.238
| JobStore.GetAllByStatus |  Avg| 11ms| 13ms | 2ms | 17.559
| |  P99| 148ms| 150ms | 2ms | 1.350
| JobStore.GetCountByStatusAndType |  Avg| 10ms| 11ms | 1ms | 9.842
| |  P99| 172ms| 99ms | -73ms | -42.442
| JobStore.GetNewestJobByStatusesAndType |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 79ms| 87ms | 8ms | 10.101
| JobStore.Save |  Avg| 11ms| 8ms | -3ms | -28.186
| |  P99| 173ms| 72ms | -101ms | -58.213
| JobStore.UpdateOptimistically |  Avg| 7ms| 6ms | -1ms | -14.997
| |  P99| 50ms| 43ms | -7ms | -14.017
| JobStore.UpdateStatus |  Avg| 6ms| 7ms | 1ms | 15.509
| |  P99| 50ms| 49ms | -1ms | -2.003
| JobStore.UpdateStatusOptimistically |  Avg| 9ms| 8ms | -1ms | -11.124
| |  P99| 83ms| 50ms | -33ms | -39.675
| LinkMetadataStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 87ms| 89ms | 2ms | 2.298
| LinkMetadataStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 72ms| 90ms | 18ms | 24.828
| PluginStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 47ms| 48ms | 1ms | 2.127
| PluginStore.Get |  Avg| 2ms| 0s | -2ms | -132.031
| |  P99| 5ms| 0s | -5ms | -101.010
| PluginStore.List |  Avg| 12ms| 9ms | -3ms | -26.034
| |  P99| 136ms| 127ms | -9ms | -6.618
| PluginStore.SetWithOptions |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 93ms| 92ms | -1ms | -1.080
| PostAcknowledgementStore.GetForPost |  Avg| 6ms| 5ms | -1ms | -15.628
| |  P99| 63ms| 47ms | -16ms | -25.436
| PostAcknowledgementStore.GetForPosts |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 147ms| 153ms | 6ms | 4.085
| PostPersistentNotificationStore.DeleteExpired |  Avg| 4ms| 8ms | 4ms | 90.192
| |  P99| 70ms| 83ms | 13ms | 18.701
| PostPersistentNotificationStore.Get |  Avg| 5ms| 8ms | 3ms | 59.742
| |  P99| 44ms| 88ms | 44ms | 99.061
| PostPersistentNotificationStore.GetSingle |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 76ms| 75ms | -1ms | -1.312
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 5ms| 22ms | 17ms | 314.238
| |  P99| 24ms| 49ms | 25ms | 102.454
| PostPriorityStore.GetForPost |  Avg| 8ms| 5ms | -3ms | -39.370
| |  P99| 94ms| 65ms | -29ms | -30.768
| PostPriorityStore.GetForPosts |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 156ms| 163ms | 7ms | 4.502
| PostStore.AnalyticsPostCount |  Avg| 306ms| 299ms | -7ms | -2.291
| |  P99| 498ms| 498ms | 0s | 0.000
| PostStore.Delete |  Avg| 32ms| 44ms | 12ms | 37.846
| |  P99| 232ms| 412ms | 180ms | 77.420
| PostStore.Get |  Avg| 21ms| 22ms | 1ms | 4.781
| |  P99| 222ms| 226ms | 4ms | 1.801
| PostStore.GetEtag |  Avg| 10ms| 11ms | 1ms | 10.271
| |  P99| 99ms| 121ms | 22ms | 22.144
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 5ms | 1ms | 22.399
| |  P99| 49ms| 52ms | 3ms | 6.109
| PostStore.GetPostIdBeforeTime |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 91ms | 1ms | 1.110
| PostStore.GetPostReminderMetadata |  Avg| 11ms| 8ms | -3ms | -26.473
| |  P99| 145ms| 53ms | -92ms | -63.451
| PostStore.GetPostReminders |  Avg| 14ms| 25ms | 11ms | 77.253
| |  P99| 82ms| 219ms | 137ms | 168.098
| PostStore.GetPosts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 58ms| 67ms | 9ms | 15.604
| PostStore.GetPostsAfter |  Avg| 10ms| 9ms | -1ms | -10.036
| |  P99| 109ms| 92ms | -17ms | -15.553
| PostStore.GetPostsBefore |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 122ms| 133ms | 11ms | 9.047
| PostStore.GetPostsByIds |  Avg| 3ms| 13ms | 10ms | 398.092
| |  P99| 10ms| 49ms | 39ms | 397.961
| PostStore.GetPostsByThread |  Avg| 13ms| 14ms | 1ms | 7.605
| |  P99| 91ms| 96ms | 5ms | 5.481
| PostStore.GetPostsSince |  Avg| 23ms| 24ms | 1ms | 4.422
| |  P99| 191ms| 204ms | 13ms | 6.811
| PostStore.GetSingle |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 83ms| 85ms | 2ms | 2.403
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 268ms| 253ms | -15ms | -5.587
| PostStore.SearchPostsForUser |  Avg| 65ms| 71ms | 6ms | 9.280
| |  P99| 2.019s| 2.488s | 469ms | 23.225
| PostStore.SetPostReminder |  Avg| 21ms| 16ms | -5ms | -23.801
| |  P99| 196ms| 180ms | -16ms | -8.164
| PostStore.Update |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 185ms| 180ms | -5ms | -2.710
| PreferenceStore.DeleteCategoryAndName |  Avg| 16ms| 9ms | -7ms | -44.105
| |  P99| 198ms| 83ms | -115ms | -58.226
| PreferenceStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 100ms| 99ms | -1ms | -1.000
| PreferenceStore.GetAll |  Avg| 6ms| 7ms | 1ms | 15.858
| |  P99| 83ms| 90ms | 7ms | 8.426
| PreferenceStore.Save |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 229ms| 229ms | 0s | 0.000
| ProductNoticesStore.ClearOldNotices |  Avg| 24ms| 28ms | 4ms | 16.405
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 58ms| 60ms | 2ms | 3.440
| |  P99| 463ms| 468ms | 5ms | 1.080
| ReactionStore.GetForPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 77ms| 75ms | -2ms | -2.614
| RoleStore.ChannelHigherScopedPermissions |  Avg| 6ms| 28ms | 22ms | 368.066
| |  P99| 25ms| 224ms | 199ms | 805.665
| RoleStore.GetByNames |  Avg| 0s| 50ms | 50ms | 14430194.265
| |  P99| 5ms| 246ms | 241ms | 4868.670
| SessionStore.Get |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 192ms| 187ms | -5ms | -2.607
| SessionStore.GetLRUSessions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 53ms| 63ms | 10ms | 18.956
| SessionStore.GetSessionsExpired |  Avg| 5ms| 4ms | -1ms | -21.314
| |  P99| 46ms| 46ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 6ms| 7ms | 1ms | 16.727
| |  P99| 67ms| 84ms | 17ms | 25.291
| SessionStore.Remove |  Avg| 10ms| 5ms | -5ms | -52.618
| |  P99| 84ms| 34ms | -50ms | -59.346
| SessionStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 98ms| 110ms | 12ms | 12.221
| SessionStore.UpdateLastActivityAt |  Avg| 9ms| 8ms | -1ms | -11.732
| |  P99| 80ms| 80ms | 0s | 0.000
| StatusStore.Get |  Avg| 5ms| 8ms | 3ms | 62.490
| |  P99| 67ms| 96ms | 29ms | 43.104
| StatusStore.GetByIds |  Avg| 12ms| 14ms | 2ms | 17.337
| |  P99| 152ms| 180ms | 28ms | 18.374
| StatusStore.SaveOrUpdate |  Avg| 22ms| 19ms | -3ms | -13.351
| |  P99| 346ms| 285ms | -61ms | -17.648
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 195ms| 189ms | -6ms | -3.085
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 80ms| 81ms | 1ms | 1.243
| SystemStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 71ms| 78ms | 7ms | 9.821
| TeamStore.Get |  Avg| 7ms| 6ms | -1ms | -15.209
| |  P99| 79ms| 81ms | 2ms | 2.535
| TeamStore.GetActiveMemberCount |  Avg| 56ms| 64ms | 8ms | 14.344
| |  P99| 99ms| 208ms | 109ms | 109.838
| TeamStore.GetAllPage |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 79ms| 87ms | 8ms | 10.087
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 6ms| 7ms | 1ms | 16.468
| |  P99| 81ms| 90ms | 9ms | 11.160
| TeamStore.GetMany |  Avg| 5ms| 20ms | 15ms | 290.756
| |  P99| 24ms| 96ms | 72ms | 296.548
| TeamStore.GetMember |  Avg| 4ms| 5ms | 1ms | 28.323
| |  P99| 40ms| 69ms | 29ms | 72.333
| TeamStore.GetTeamsByUserId |  Avg| 5ms| 6ms | 1ms | 18.369
| |  P99| 77ms| 85ms | 8ms | 10.429
| TeamStore.GetTeamsForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 77ms| 85ms | 8ms | 10.336
| TeamStore.GetTotalMemberCount |  Avg| 51ms| 60ms | 9ms | 17.706
| |  P99| 206ms| 229ms | 23ms | 11.138
| TeamStore.SaveMember |  Avg| 35ms| 36ms | 1ms | 2.853
| |  P99| 227ms| 231ms | 4ms | 1.761
| ThreadStore.Get |  Avg| 6ms| 7ms | 1ms | 16.345
| |  P99| 63ms| 86ms | 23ms | 36.582
| ThreadStore.GetMembershipForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 97ms| 96ms | -1ms | -1.036
| ThreadStore.GetTeamsUnreadForUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 97ms| 105ms | 8ms | 8.286
| ThreadStore.GetThreadFollowers |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 78ms| 81ms | 3ms | 3.853
| ThreadStore.GetThreadForUser |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 171ms| 177ms | 6ms | 3.514
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 15ms| 16ms | 1ms | 6.585
| |  P99| 97ms| 98ms | 1ms | 1.032
| ThreadStore.GetThreadsForUser |  Avg| 12ms| 13ms | 1ms | 8.010
| |  P99| 131ms| 145ms | 14ms | 10.659
| ThreadStore.GetTotalThreads |  Avg| 6ms| 7ms | 1ms | 16.546
| |  P99| 80ms| 87ms | 7ms | 8.778
| ThreadStore.GetTotalUnreadMentions |  Avg| 6ms| 7ms | 1ms | 15.812
| |  P99| 80ms| 88ms | 8ms | 10.010
| ThreadStore.GetTotalUnreadThreads |  Avg| 6ms| 7ms | 1ms | 16.505
| |  P99| 79ms| 87ms | 8ms | 10.078
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 6ms| 7ms | 1ms | 15.847
| |  P99| 82ms| 88ms | 6ms | 7.315
| ThreadStore.MaintainMembership |  Avg| 17ms| 16ms | -1ms | -5.800
| |  P99| 205ms| 200ms | -5ms | -2.441
| ThreadStore.MarkAllAsReadByChannels |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 88ms| 90ms | 2ms | 2.262
| ThreadStore.MarkAllAsReadByTeam |  Avg| 14ms| 11ms | -3ms | -21.189
| |  P99| 95ms| 48ms | -47ms | -49.474
| ThreadStore.MarkAsRead |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 79ms| 80ms | 1ms | 1.269
| ThreadStore.UpdateMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 78ms| 79ms | 1ms | 1.283
| TokenStore.Cleanup |  Avg| 8ms| 27ms | 19ms | 240.125
| |  P99| 25ms| 99ms | 74ms | 301.424
| UserAccessTokenStore.GetByToken |  Avg| 7ms| 8ms | 1ms | 13.775
| |  P99| 151ms| 83ms | -68ms | -45.037
| UserStore.AutocompleteUsersInChannel |  Avg| 63ms| 68ms | 5ms | 7.948
| |  P99| 248ms| 249ms | 1ms | 0.404
| UserStore.Count |  Avg| 17ms| 28ms | 11ms | 66.433
| |  P99| 48ms| 216ms | 168ms | 348.187
| UserStore.Get |  Avg| 6ms| 9ms | 3ms | 49.511
| |  P99| 84ms| 96ms | 12ms | 14.231
| UserStore.GetAllProfiles |  Avg| 5ms| 6ms | 1ms | 18.527
| |  P99| 52ms| 62ms | 10ms | 19.171
| UserStore.GetAllProfilesInChannel |  Avg| 338ms| 326ms | -12ms | -3.553
| |  P99| 1.665s| 1.626s | -39ms | -2.343
| UserStore.GetByUsername |  Avg| 10ms| 13ms | 3ms | 30.694
| |  P99| 99ms| 176ms | 77ms | 77.734
| UserStore.GetForLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 77ms| 82ms | 5ms | 6.515
| UserStore.GetMany |  Avg| 5ms| 8ms | 3ms | 55.476
| |  P99| 77ms| 70ms | -7ms | -9.091
| UserStore.GetProfileByIds |  Avg| 10ms| 11ms | 1ms | 10.077
| |  P99| 111ms| 121ms | 10ms | 9.021
| UserStore.GetProfilesByUsernames |  Avg| 11ms| 12ms | 1ms | 8.898
| |  P99| 122ms| 134ms | 12ms | 9.810
| UserStore.GetProfilesInChannel |  Avg| 20ms| 15ms | -5ms | -24.845
| |  P99| 224ms| 188ms | -36ms | -16.036
| UserStore.GetProfilesNotInChannel |  Avg| 18ms| 12ms | -6ms | -34.072
| |  P99| 206ms| 86ms | -120ms | -58.113
| UserStore.GetUnreadCount |  Avg| 7ms| 8ms | 1ms | 14.019
| |  P99| 80ms| 90ms | 10ms | 12.502
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 36ms| 40ms | 4ms | 11.170
| UserStore.Save |  Avg| 87ms| 89ms | 2ms | 2.289
| |  P99| 319ms| 325ms | 6ms | 1.881
| UserStore.Search |  Avg| 27ms| 30ms | 3ms | 10.957
| |  P99| 206ms| 219ms | 13ms | 6.323
| UserStore.Update |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 207ms| 218ms | 11ms | 5.318
| UserStore.UpdateFailedPasswordAttempts |  Avg| 7ms| 8ms | 1ms | 13.845
| |  P99| 79ms| 84ms | 5ms | 6.297
| UserStore.UpdateLastLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 53ms| 50ms | -3ms | -5.616
| UserStore.UpdateUpdateAt |  Avg| 6ms| 7ms | 1ms | 15.450
| |  P99| 48ms| 49ms | 1ms | 2.062
| UserTermsOfServiceStore.GetByUser |  Avg| 5ms| 6ms | 1ms | 19.716
| |  P99| 73ms| 82ms | 9ms | 12.304
| WebhookStore.GetOutgoingByTeam |  Avg| 12ms| 13ms | 1ms | 8.041
| |  P99| 144ms| 150ms | 6ms | 4.158
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 523ms| 458ms | -65ms | -12.417
| | P99| 2.374s| 2.271s | -103ms | -4.339
| addTeamMember | Avg| 1.049s| 1.028s | -21ms | -2.003
| | P99| 4.902s| 4.88s | -22ms | -0.449
| autocompleteChannelsForTeamForSearch | Avg| 55ms| 51ms | -4ms | -7.270
| | P99| 238ms| 242ms | 4ms | 1.678
| autocompleteUsers | Avg| 56ms| 60ms | 4ms | 7.152
| | P99| 247ms| 249ms | 2ms | 0.811
| createCategoryForTeamForUser | Avg| 110ms| 50ms | -60ms | -54.778
| | P99| 483ms| 99ms | -384ms | -79.585
| createChannel | Avg| 654ms| 558ms | -96ms | -14.679
| | P99| 2.355s| 2.395s | 40ms | 1.699
| createDirectChannel | Avg| 624ms| 536ms | -88ms | -14.096
| | P99| 2.433s| 2.407s | -26ms | -1.069
| createEmoji | Avg| 7ms| 0s | -7ms | -105.722
| | P99| 10ms| 0s | -10ms | -100.503
| createGroupChannel | Avg| 1.06s| 827ms | -233ms | -21.979
| | P99| 4.45s| 4.054s | -396ms | -8.899
| createPost | Avg| 674ms| 563ms | -111ms | -16.464
| | P99| 3.664s| 2.76s | -904ms | -24.671
| createUser | Avg| 283ms| 252ms | -31ms | -10.945
| | P99| 1.838s| 1.449s | -389ms | -21.169
| deleteDraft | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 161ms| 170ms | 9ms | 5.593
| deletePost | Avg| 56ms| 76ms | 20ms | 35.790
| | P99| 239ms| 456ms | 217ms | 90.606
| followThreadByUser | Avg| 44ms| 52ms | 8ms | 18.072
| | P99| 472ms| 433ms | -39ms | -8.269
| getAllTeams | Avg| 7ms| 8ms | 1ms | 14.471
| | P99| 94ms| 98ms | 4ms | 4.271
| getCategoriesForTeamForUser | Avg| 21ms| 24ms | 3ms | 13.996
| | P99| 212ms| 222ms | 10ms | 4.727
| getChannel | Avg| 29ms| 18ms | -11ms | -37.817
| | P99| 249ms| 197ms | -52ms | -20.903
| getChannelMember | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 200ms| 204ms | 4ms | 1.999
| getChannelMembers | Avg| 10ms| 7ms | -3ms | -30.234
| | P99| 48ms| 24ms | -24ms | -49.612
| getChannelMembersForTeamForUser | Avg| 11ms| 12ms | 1ms | 9.187
| | P99| 110ms| 130ms | 20ms | 18.214
| getChannelMembersForUser | Avg| 6ms| 8ms | 2ms | 31.055
| | P99| 77ms| 85ms | 8ms | 10.357
| getChannelStats | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 92ms| 95ms | 3ms | 3.273
| getChannelUnread | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 160ms| 163ms | 3ms | 1.875
| getChannelsForTeamForUser | Avg| 11ms| 12ms | 1ms | 9.053
| | P99| 130ms| 143ms | 13ms | 10.020
| getChannelsForUser | Avg| 5ms| 6ms | 1ms | 18.321
| | P99| 66ms| 87ms | 21ms | 31.628
| getClientConfig | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 211ms| 215ms | 4ms | 1.895
| getDrafts | Avg| 13ms| 14ms | 1ms | 7.731
| | P99| 166ms| 161ms | -5ms | -3.020
| getFilePreview | Avg| 61ms| 63ms | 2ms | 3.285
| | P99| 301ms| 322ms | 21ms | 6.977
| getFileThumbnail | Avg| 52ms| 54ms | 2ms | 3.812
| | P99| 248ms| 249ms | 1ms | 0.403
| getPostThread | Avg| 48ms| 50ms | 2ms | 4.144
| | P99| 432ms| 434ms | 2ms | 0.463
| getPostsForChannel | Avg| 89ms| 94ms | 5ms | 5.610
| | P99| 893ms| 915ms | 22ms | 2.464
| getPostsForChannelAroundLastUnread | Avg| 33ms| 35ms | 2ms | 6.076
| | P99| 355ms| 368ms | 13ms | 3.660
| getPreferences | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 87ms| 92ms | 5ms | 5.746
| getProfileImage | Avg| 80ms| 69ms | -11ms | -13.748
| | P99| 477ms| 465ms | -12ms | -2.516
| getPublicChannelsForTeam | Avg| 27ms| 28ms | 1ms | 3.734
| | P99| 195ms| 218ms | 23ms | 11.802
| getTeamMember | Avg| 10ms| 11ms | 1ms | 9.562
| | P99| 100ms| 136ms | 36ms | 36.031
| getTeamMembersForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 89ms| 93ms | 4ms | 4.476
| getTeamStats | Avg| 81ms| 71ms | -10ms | -12.403
| | P99| 428ms| 229ms | -199ms | -46.548
| getTeamsForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 80ms| 86ms | 6ms | 7.545
| getTeamsUnreadForUser | Avg| 12ms| 13ms | 1ms | 8.038
| | P99| 185ms| 194ms | 9ms | 4.865
| getThreadsForUser | Avg| 12ms| 13ms | 1ms | 8.070
| | P99| 150ms| 157ms | 7ms | 4.662
| getUser | Avg| 9ms| 10ms | 1ms | 10.760
| | P99| 178ms| 190ms | 12ms | 6.740
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 42ms| 49ms | 7ms | 16.801
| getUsers | Avg| 9ms| 10ms | 1ms | 10.536
| | P99| 166ms| 179ms | 13ms | 7.851
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 43ms| 41ms | -2ms | -4.644
| getUsersByNames | Avg| 12ms| 13ms | 1ms | 8.416
| | P99| 142ms| 145ms | 3ms | 2.119
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 99ms| 106ms | 7ms | 7.073
| login | Avg| 228ms| 99ms | -129ms | -56.592
| | P99| 2.262s| 628ms | -1.634s | -72.246
| logout | Avg| 164ms| 93ms | -71ms | -43.345
| | P99| 487ms| 419ms | -68ms | -13.967
| patchPost | Avg| 113ms| 70ms | -43ms | -37.957
| | P99| 1.3s| 599ms | -701ms | -53.919
| removeUserCustomStatus | Avg| 360ms| 335ms | -25ms | -6.946
| | P99| 1.205s| 1.405s | 200ms | 16.597
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 31ms| 33ms | 2ms | 6.393
| | P99| 242ms| 246ms | 4ms | 1.651
| searchAllChannels | Avg| 46ms| 47ms | 1ms | 2.183
| | P99| 225ms| 226ms | 1ms | 0.444
| searchGroupChannels | Avg| 13ms| 14ms | 1ms | 7.661
| | P99| 142ms| 151ms | 9ms | 6.349
| searchPostsInTeam | Avg| 83ms| 91ms | 8ms | 9.658
| | P99| 2.082s| 2.489s | 407ms | 19.550
| searchUsers | Avg| 29ms| 31ms | 2ms | 6.933
| | P99| 211ms| 222ms | 11ms | 5.206
| setPostReminder | Avg| 49ms| 50ms | 1ms | 2.026
| | P99| 410ms| 441ms | 31ms | 7.561
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 48ms| 47ms | -1ms | -2.095
| | P99| 391ms| 368ms | -23ms | -5.879
| updateCategoriesForTeamForUser | Avg| 117ms| 138ms | 21ms | 17.884
| | P99| 650ms| 919ms | 269ms | 41.382
| updatePreferences | Avg| 36ms| 34ms | -2ms | -5.553
| | P99| 344ms| 294ms | -50ms | -14.545
| updateReadStateAllThreadsByUser | Avg| 14ms| 11ms | -3ms | -21.030
| | P99| 95ms| 48ms | -47ms | -49.474
| updateReadStateThreadByUser | Avg| 117ms| 114ms | -3ms | -2.565
| | P99| 762ms| 705ms | -57ms | -7.477
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 564ms| 572ms | 8ms | 1.419
| | P99| 2.233s| 2.261s | 28ms | 1.254
| upsertDraft | Avg| 14ms| 15ms | 1ms | 6.920
| | P99| 175ms| 186ms | 11ms | 6.284
| viewChannel | Avg| 36ms| 45ms | 9ms | 24.910
| | P99| 357ms| 429ms | 72ms | 20.147
